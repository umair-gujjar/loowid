Loowid
======

*LOOk What I'm Doing* is a web application that allows you to connect with other users and share audio, video, screen and files without any plugin using WebRTC technology.

https://www.loowid.com
  
Install
=======

  1. You need to install node.js and mongo before run loowid.
  2. Download source code.
  3. Create and download public and private keys of your self-signed certificate.
  
      http://www.cert-depot.com/ 
  4. Create a data folder to store mongodb.
  
      mongod --dbpath data
  5. Run >npm install
  6. Run >sudo node server.js
  7. Connect to https://localhost/

Docker
=======

	Too much steps to install? Don't worry loowid is also dockerized !!
	
	https://github.com/loowid/loowid-docker
  
Modify
=======

  1. Add your changes to the source.
  2. If you change client side javascript files you have to generate public minified files.
  
      grunt mini
  
