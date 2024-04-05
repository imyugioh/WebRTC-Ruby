#WebRTC Rails


This is a basic application I have build to test WebRTC, my main objective is to practice WebRTC. I will slowly improve the application, and add more features each time.

##Start Now

To start the project and test is at your own you have to do the following:

1. Clone the repo: ```git@github.com:raptor1001/WebRTC-Ruby.git```
2. Install all the gems with ```bundle install```
3. Go to ```app/rtc/``` and run ```npm install``` to install ```socket.io```
4. Check to see your IP: ```ifconfig```, copy the IP and change the ones in ```public/javascripts/rtc/client_signaling.js``` and at the first line change the ```io.connect('YOUR-IP:2013')```
5. Open the server ```rails server```
6. Open the NodeJs server ```node app/rtc/server.js```
7. Go to the URL: ```localhost:3000```
8. ENJOY!

##Test it in production

Here you have the [link](http://webrtc-rails.layeris.com)

~~**At the moment it only works between Chrome and Chrome (I'm currently working on the problem)**~~

Now it works on Chrome and Firefox. Maybe there was some bug on the API.


##Objectives

As I said before the main objective is to practice WebRTC but I will list some of the other objectives I have in mind:

1. **DONE** WebRTC between 2 peers
2. **DONE** Clean the webpage of unneeded menus, just the Home page and a page to call
3. **DONE** Add a chat module (with NodeJs, latter can be improved to be with arbitrary data with RTCDataChannel)
4. Change the NodeJS server to a native Ruby (EventMachine)
5. Control of errors in the Call (on of the Peers leave ... etc)
6. **DONE** Ability to create your own rooms with different names, and to setup an user name (for the Chat)
7. Ability to activate and deactivate Video or Audio, and reactivate them 
8. Room with more than 2 Peers
9. Change the Chat from NodeJS to WebRTC DataChannel

