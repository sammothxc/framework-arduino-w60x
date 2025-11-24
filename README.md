# W600 Arduino Getting Started Guide

## 1. Introduction

[Arduino](https://baike.baidu.com/item/Arduino) is a convenient, flexible, and easy-to-use open-source electronic prototyping platform. Now, the W60x chip directly supports Arduino development, allowing developers to write code using familiar Arduino functions and libraries and run it directly on the W60x without an external microcontroller. This makes product design easier for developers.

## 2. Prerequisites

-  1 x W60x development board [TB-01 recommended](http://shop.thingsturn.com)）
-  1 × Micro USB B cable
-  1 × PC（Currently only available for Windows environments）

## 3. Environment Setup

1. Download the Arduino IDE development environment from https://www.arduino.cc/en/Main/Software. It is recommended to use the latest version.

2. Power on the Arduino and open the "Preferences" window. Add the following URL to the Attach Board Manager: `http://arduino.w600.fun/package_w600_index.json`
![](doc/img/1556334078542.png)

3. Open the menu: Tools -> Development Board -> Development Board Manager
![](doc/img/1556334412321.png)

4. Enter keywords in the input box, `w600` w600select the latest version `0.2.4`）, and click [Install].
![](doc/img/1556334650002.png)
![](doc/img/1556335438851.png)

5. Select the TB-01 development board and configure its parameters (note the importance of selecting the correct communication port and speed).
![](doc/img/1556335475972.png)

**Port:** You can check the corresponding port in your computer's Device Manager.

**Upload Speed:** The communication rate during burning, the default is 2Mbps, you can choose 115200 if the download fails.

**Upload Files:** Download file format (default is IMG; if the download fails or secboot needs to be updated, you can select FLS).
![](doc/img/28194943723.jpeg)

6. Selecting "File" -> "Examples" allows you to try out some examples for flashing tests, such as "Blink".
![](doc/img/1556335587121.png)

7. Click Upload to download the firmware.
![](doc/img/1556438775082.png)

8.  The result after running is as follows
![](doc/img/1556415104023.png)

Meanwhile, you can see the indicator lights on the development board flashing continuously.

## 4. Other

For any questions or suggestions, please ask them at the Q&A community https://ask.w600.fun