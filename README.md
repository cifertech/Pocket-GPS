<div align="center">

  <img src="https://user-images.githubusercontent.com/62047147/195847997-97553030-3b79-4643-9f2c-1f04bba6b989.png" alt="logo" width="100" height="auto" />
  <h1>Pocket-GPS</h1>
   
  <p>
    Simple project w/ GPS Neo-6m and ESP32
  </p>
   

 
<!-- Badges -->

<a href="https://github.com/cifertech/Pocket-GPS" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=cifertech&message=Pocket-GPS&color=white&logo=github" alt="cifertech - Pocket-GPS"></a>
<a href="https://github.com/cifertech/Pocket-GPS"><img src="https://img.shields.io/github/stars/cifertech/Pocket-GPS?style=social" alt="stars - Pocket-GPS"></a>
<a href="https://github.com/cifertech/Pocket-GPS"><img src="https://img.shields.io/github/forks/cifertech/Pocket-GPS?style=social" alt="forks - Pocket-GPS"></a>
   
<h4>
    <a href="https://twitter.com/cifertech1">TWITTER</a>
  <span> · </span>
    <a href="https://www.instagram.com/cifertech/">INSTAGRAM</a>
  <span> · </span>
    <a href="https://www.youtube.com/c/cifertech">YOUTUBE</a>
  <span> · </span>
    <a href="https://cifertech.net/">WEBSITE</a>
  </h4>
</div> 
 
<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Pictures](#camera-Pictures)
  * [Features](#dart-features)
- [Getting Started](#toolbox-getting-started)
  * [Schematic](#electric_plug-Schematic)
  * [Installation](#gear-installation)
- [License](#warning-license)
- [Contact](#handshake-contact)

  

<!-- About the Project -->
## :star2: About the Project
in this project, with the help of GPS Neo-6M, We receive and display the values of Altitude, Latitude, Longitude, and Speed. also using TFT LCD I created a beautiful user interface for it.

<!-- Pictures -->
### :camera: Pictures

<div align="center"> 
  <img src="https://user-images.githubusercontent.com/62047147/210238038-c258c174-d6a5-4117-bd56-f4b2b8d9549c.jpg" alt="screenshot" width="Auto" height="Auto" />
</div>


<!-- Features -->
### :dart: Features

Display the Values of:

- Altitude
- Latitude, Longitude
- Speed
- Number of Satellite

<!-- Getting Started -->
## 	:toolbox: Getting Started

We use st7735 Tft Lcd with ESP32. Also, I used a GPS Neo-6m in order to receive the GPS values.

- GPS Neo-6M
- TFT Lcd st7735
- ESP32

<img src="https://user-images.githubusercontent.com/62047147/210239204-61dd2d43-4608-4058-b47c-69ff7fab72ee.png" alt="screenshot" width="Auto" height="500" />

<!-- Schematic -->
### :electric_plug: Schematic
Make the connections according to the table and schematic below.

* ESP32 and GPS Neo-6M.

| ESP32 | GPS Neo-6M |
| ----  | -----|
| 34    | TXD  |
| 35    | RXD  |

<img src="https://user-images.githubusercontent.com/62047147/210239544-e20ed1c6-7e17-4b27-8215-d5b444af73be.png" alt="screenshot" width="400" height="auto" />


* ESP32 and st7735 tft LCD.

| ESP32 | TFT Lcd |  
| ----  | ----- |
| 14 | CS   |
| 33 | RST  |
| 27 | DC   |
| 18 | CLK  |
| 23 | DIN  |
| 5V | VCC  |
| 3V3 | LED |
| GND | GND |

<img src="https://user-images.githubusercontent.com/62047147/196051634-6a0f5314-96a1-4bf7-8b82-00e6b0c39f1e.png" alt="screenshot" width="800" height="auto" />



<!-- Installation -->
### :gear: Installation

Before uploading the code you need to install ESP32 in your Arduino IDE

- In Arduino IDE, go to File > Preferences
- Enter URLs Additional Boards Manager URLs field. Then, click the “OK”

```bash
  https://dl.espressif.com/dl/package_esp32_index.json
```

Then you need to install the required library in Arduino IDE. Follow these steps:

- Follow this path Sketch> Include Library> Manage Libraries
- Search for Adafruit_ST7735 and TinyGPS++
- Install the library


<!-- License --> 
## :warning: License
 
Distributed under the MIT License. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact 

CiferTech - [@twitter](https://twitter.com/cifertech1) - CiferTech@gmali.com

Project Link: [https://github.com/cifertech/Pocket-GPS](https://github.com/cifertech/Pocket-GPS)

