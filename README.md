# LCD_Camera_drivers

## Abstract
This project records live stream through camera and displays it on LCD through SJ One microcontroller which is LPC 1758. This camera has longer battery as it runs through portable battery powering microcontroller. As there are many High Quality Cameras available in market, purpose of this camera is found in applications where streaming of medium quality video/photo is required for longer period of time and camera has to survive longer on single battery, which can’t be provided by handy digital camera. Another functionality provided by this project is to enable user to capture images on SD card and view it on LCD providing different resolution and modes as option through interactive UI designed on LCD. Project Hardware enclosed in small box 3D designed for this project enables portability and ease of access to user.

## Objectives & Introduction

The objective of this project was to learn how timing and buffer play an important role in capturing the pixels from the camera and displaying them on the LCD screen. The following hard objectives were set for the project:


1. Write a driver for the SPI camera ov2640, which has a better rate of capturing the image with the SJONE board. 
2. Write the driver for the LCD display (Adafruit 5' TFT) and integrate it by choosing the right resolution. 
3. Implement a menu class for different options of the camera on the LCD and program external buttons for navigating across the menu. 
4. Integrate the camera and LCD by displaying the output of the camera on the LCD. 
5. Store the output of the camera on the SD card, if capture mode is selected from LCD menu. 
6. Read the image from the SD card and display on the screen.
