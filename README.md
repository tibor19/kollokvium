# Kollokvium (colloquium)

## about
Kollokvium is an example web-based real time chat application that utilises the thor-io vnext libraries' WebRTC API functionality. 

It allows you to create and join chat rooms and is capable of web based video & audio streaming along with screen & file sharing and ofcourse, real time text chat. 

It is an all in one solution that requires no installation, and is compatible with most modern browsers.

You can try it at this link https://kollokvium.herokuapp.com/

## feature list

1. 1-n participants
2. Instant Messages (chat)
3. File share ( files sent to chat window)
4. Screen sharing ( deskop)
5. Random room generator or user defined
6. No login and registration required
7. Multiple stream recording ( record the meeting )
8. Customizable

## in-progress

The following features are right now being developed by the Kollokvium team.

1. Broadcast - Possibility to host a 'broadcast/webcast" using p2p chains (1-n many)
2. Add pre-recorded local media streams such as (video,audio) to conference/call
3. Chromecast integration
4. Smartphone & Tablet UI working properly

We count on having this three first features up and running no later than end of march 2020.

## install 

1. Clone this repo
2. Run npm install 
3. Run npm start to start local-server at http://localhost:1337 
4. Modify & compile
5. Make sure you run weback , or put it on watch 

## quick customization guide.

Clone/download the this repo, modify settings.json in found in the ./client folder, compile and run webpack.

### settings.json

    {
    "domain": "Kollokvium", // name of your app
    "contextPrefix": "kollokvium", // your prefix for 'signals', rooms, negotiation etc. hidden for user
    "serverUrl": "wss://kollokvium.herokuapp.com", // server url, use this if you just want to host app ( html, js, css ) , othewise change.
    "version": "1.0.5" // just the version
    }

## Set up on host
 
If you want to host "only" client, copy index.html, img,build and css folders into your site and/or folder.  To host application deploy all in your hosting enviorment. 

## other

Goodluck, and if you find issues, have ides post them here 
https://github.com/MagnusThor/kollokvium/issues

Regards

 Team Kollokvium
 
