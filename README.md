**Upload Image**
==================
This is a simple utility for uploading image files on various free image hostings like imageshack.us. 
Idea and some code of program was inspired by Photo Uploader software. This repo is a mirror of https://code.google.com/p/upload-image/

####Installation:
This repo can be installed using the python package manager:
```pip install upload-image```

####Usage:
Just type in the terminal emulator something like:
```upload-image -s imageshack.us google-logo.png```
<a href="http://imgur.com/34B5Fhv"><img src="http://i.imgur.com/34B5Fhv.png" title="Hosted by imgur.com" /></a>

####Features:
  * Upload image to the remote server
  * Display direct link to the uploaded image file

####Structure:
Program has modular structure so it's easy to implement support ofnew image hosting service.

####Currently (SVN-version) supports the following services:
 * imageshack.us
 * radikal.ru
 * picoodle.com is not supported anymore because it's blocked anonymous upload.
