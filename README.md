# QR Code Generator
This is a simple Node.js application that allows you to generate a QR code image from a URL. You can also save the URL and the QR code image in a text file and a png file respectively.

# Installation
To run this application, you need to have Node.js installed on your system. You also need to install the following npm packages:

- [inquirer]: A collection of common interactive command line user interfaces.
- [qr-image]: A module to generate QR Code images in either PNG, SVG, EPS or PDF formats.
- [fs]: A native Node.js module that provides an API for interacting with the file system.

You can install these packages by running the following command in your terminal:
```
npm install inquirer qr-image fs
```
To use this application, you need to run the following command in your terminal:
```
node index.js
```
This will prompt you to type in your URL. After you enter your URL, the application will display it on the console and generate a QR code image from it. The application will also create a text file named URL.txt that contains your URL and a png file named qr_image.png that contains your QR code image. 

You can find these files in the same directory as your index.js file.
