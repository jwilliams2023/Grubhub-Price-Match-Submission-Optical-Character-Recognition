# Grubhub Price Match Guarantee Automation

## Overview
This is a **Grubhub Price Match Guarantee** website automation script that decreases the time needed to submit proof of a lower-price cart found elsewhere.

When you run this script, it will look similar to this:

![Demo Video](https://github.com/jwilliams2023/Grubhub-Price-Match-Submission-OCR/blob/master/Resources/DemoVideo.gif)

*Note: At the end of the GIF, I manually submitted the image proof, but there is a line of code that just needs to be uncommented to auto-submit. I keep it commented out since I want to be 100% sure everything is accurate.*

## Requirements
Several modules and libraries are required to run the script:
- **Selenium** (for browser automation)
- **Chrome WebDriver** (for controlling Chrome)
- **Tesseract OCR** (for optical character recognition)
- **pyautogui** (for automating keyboard and mouse actions)

### Documentation and Downloads:
- Selenium: [Selenium Documentation](https://www.selenium.dev/documentation/overview/)
- Chrome WebDriver: [Download Chrome WebDriver](https://chromedriver.chromium.org/downloads)
- Tesseract OCR: [Tesseract Installation Guide](https://github.com/UB-Mannheim/tesseract/wiki)

## Setup Instructions

1. **Download Directory Path**  
   Set the path for the download directory where the image of your cart will be stored. By default, mine is the most recent image in my downloads folder since that is where I store snips of the carts.

2. **Tesseract Setup**  
   Specify the path for the `tesseract.exe` file. You can find this in your Tesseract installation folder. Here's an example of how this looks in the script:

   ![Tesseract Path](https://github.com/jwilliams2023/Grubhub-Price-Match-Submission-OCR/assets/130696072/cbff4012-b5f9-4e9b-87e3-4701d7b24886)

3. **Chrome WebDriver Setup**  
   Specify the location of your downloaded Chrome WebDriver. Additionally, I have personalized the script to open Chrome using my signed-in user data, so that I can be automatically signed in to Grubhub. This setup looks like this:

   ![Chrome WebDriver Setup](https://github.com/jwilliams2023/Grubhub-Price-Match-Submission-OCR/assets/130696072/76592c96-b188-4037-b798-77fd646ec622)

## Running the Script

1. **Ensure Setup Is Complete**  
   Before running the script, ensure that all required paths (download directory, Tesseract path, and Chrome WebDriver location) are correctly set.

2. **Auto-Submit**  
   If you prefer to auto-submit your image proof, uncomment the line of code responsible for submission. This option is commented out by default to give you the opportunity to manually verify accuracy before submission.

3. **Run the Script**  
   Once everything is set up, simply run the script, and it will automate the process of submitting your Grubhub price match claim.

## Contributing
If you'd like to contribute to this project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/jwilliams2023/Grubhub-Price-Match-Submission-OCR?tab=MIT-1-ov-file#readme) file for details.

## Contact
For any inquiries, feel free to reach out via [williams.joe3102@gmail.com](mailto:williams.joe3102@gmail.com).
