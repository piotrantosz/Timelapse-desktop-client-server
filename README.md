# Timelapse-desktop-client-server

## Desktop client server

Software made for creating long term timelapses, using diffrent devices as client server (creating timelapses) and client (managing timelapses).

![Local storage diagram](http://i.imgur.com/whu0w3w.png)

* client server - it's your device where you run our code. This device become machine for taking pictures and storaging them. Connect camera, place it, stabilize and that's all.
* client - your control panel, manage your client server from here

## Technologies

Web client
* Python Django

Android client
* Java

Desktop client server
* Java

Android client server
* Java

Communication
* Rest API

## Features

Client
* Managing frequency of taken photo and sum time (e.g. year, month, etc.) 
* Changing camera settings (e.g. brightness)
* Checking storage, status, client server machine temperatures etc. 
* Managing notifications (e.g. choose alerts and send them on your email)
* Check daily photo and make sure everything is fine

Client server
* View status of everything
* Simple connect your camera and set up everything from client
* Wake on lan for advenced users


