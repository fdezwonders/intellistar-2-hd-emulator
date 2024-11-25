# intellistar-2-hd-emulator
This is a web application that displays weather information in the same visual presentation as the now-defunct cable headend unit [Intellistar 2 HD](https://www.twcarchive.com/wiki/IntelliStar_2_HD) (also known internally as "I2 HD" or colloquially just referred to as the "I2").

## Overview
This is a local forecast segment that airs on The Weather Channel called the "Local on the 8s". The name is because it airs at timeslots that end in "8" (9:28, 2:48, etc.). The forecast is approximately a minute long and provides information on current and forecasted weather conditions. This type of forecast started in 1982 using WeatherStar units. It was later upgraded to IntelliStar in 2003 and received various graphic changes over the years becoming the IntelliStar 2. This emulator uses the style that used in 2013.

## Instructions
### Option 1 (easier)
1. Visit: <https://fdezwonders.github.io/intellistar-2-hd-emulator/>.
2. Enter zip code
3. Click start
4. Press F11 for fullscreen

### Option 2 (more customizable)
1. Extract all contents into folder
2. Run index.html in Google Chrome
3. Enter zip code
4. Click start
5. Press F11 for fullscreen

### Option 3 (Docker)
1. `docker run -p 8080:80 ghcr.io/fdezwonders/intellistar-2-hd-emulator`
2. Visit: http://localhost:8080
3. Enter zip code
4. Click start
5. Press F11 for fullscreen

## Features
Most of core animation and logic has been replicated including severe weather alerts, forecast descriptions, crawl text, and the Doppler radar map.

## Looping
To enable or disable looping, click on the TWC logo in the info-bar in the top-left corner of the emulator.

To get looping working properly, you may (as of Chrome M66) have to go to chrome://flags#autoplay-policy (Autoplay Policy) and change it to `User gesture is required for cross-origin iframes` or `No user gesture is required`  

## Note
As a note, the IntelliStar 2 HD was decommissioned around 2016, and hence, you won't see this style of Local on the 8s on The Weather Channel anymore, since local cable compaines now use the IntelliStar 2 xD (or the IntelliStar 2 Jr. for just SD feeds).
More information on the product can be found [here](https://www.twcarchive.com/wiki/IntelliStar_2_HD).

## Screenshots
![Screenshot 1](/screenshots/1.png)

![Screenshot 2](/screenshots/2.png)

![Screenshot 3](/screenshots/3.png)

![Screenshot 4](/screenshots/4.png)

![Screenshot 5](/screenshots/5.png)

![Screenshot 6](/screenshots/6.png)

![Screenshot 7](/screenshots/7.png)

![Screenshot 8](/screenshots/8.png)

![Screenshot 9](/screenshots/9.png)

![Screenshot 10](/screenshots/10.png)