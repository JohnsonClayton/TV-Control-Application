# TV Control Application
## Current Idea:
This application is made with the goal in mind of allowing a phone connect and control a television on the local area network (LAN). 
- What do we want to use?
  - Raspberry Pi
  - iPhone 
  - Skllz
- Helpful things to have
  - [Apache Cordova Basic Guide](https://cordova.apache.org/docs/en/latest/guide/cli/)
  - [Using RS232 Connections](https://www.commfront.com/pages/3-easy-steps-to-understand-and-control-your-rs232-devices)
  - [TV Manual Codes](https://www.manualslib.com/manual/451487/Sharp-Lc46sb54u-Lc-46-Lcd-Tv.html?page=28#manual)
  - Skllz
  
## Process
### Phone -> App -> Website -> Pi -> *Something* -> TV
- Step 1:
  - Set up the Pi
  - Set up an app on phone (Apache Cordova)
  - Connect to same network
- Step 2: 
  - Create hello world app that talks to local hosted web app
    - (App -> Website -> Pi)
  - Ensure input from phone
- Step 3:
  - Use commands from manual for TV to create + demonstrate control over TV with code
    - Code may be in C or other lower-level situation
- Step 4:
  - Find a way to connect the js from website and the code used to command TV
