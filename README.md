
# QR Code/Barcode Scanner using Pyzbar package

Using opencv and pyzbar packages, python program is written so as to recognize the type of code that is being displayed on the screen and decode the data to a user-readable format and open links

## Procedure

	1. Import dependencies
    2. Define a function that takes an image as a paramter
        a. Convert the image to grayscale and use in-built decode function and save it in scan_img
        b. Using a for loop, get the points and the respective x, y, width and height values.
        c. Convert it into an integer array and reshape it into a matrix
        d. Draw lines around the code withh the obtained points
        e. Put a text right next to the box with the points that displays the type of code that has been identified
    3. Run it real time


## Run Locally

Clone the project

```bash
  git clone https://github.com/adithyaravi12/code-scanner
```

Go to the project directory

```bash
  cd code-scanner
```

Install necessary dependencies 
```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Screenshots

![App Screenshot](https://github.com/adithyaravi12/code-scanner/blob/main/proj6.gif)


## 🔗 Links
[![My Portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](http://adithyaravi12.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adithya-ravi-707443126/)


