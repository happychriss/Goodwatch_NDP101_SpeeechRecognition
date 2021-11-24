##### Setup Platformio / CLION to work with EdgeImpulse and TinyML NDP101

I am using Platformio as development platform for embedded projects and CLION as my IDE. Both are integrated and together they provide a consistent way for programming, compiling and deployment - independent from the MCU/CPU used. I try to use the Arduino Libraries- as to a certain degree the provide platform independence. In addition many libraries are available for Arduino.  To facilitate the Machine Learning I rely on Edgeimpulse - an cloud platform that supports the e2e machine learning cycle - so in a nutshell:

* Platformio -  Platform for embedded development
* Clion - Integrated Development Environment with Platformio Integration
* EdgeImpulse - Development platform for machine learning on edge devices

This GitHub repository contains all the necessary settings and libraries to kick-off a development and to build in your customer code.

###More background and the original SW can be found here: https://github.com/edgeimpulse/firmware-syntiant-tinyml

##Status:
This is a draft version - not fully tested (especially the "download_model.sh" is not yet tested)
Please note that you have additionally to patch your local libraries as described here: https://github.com/edgeimpulse/firmware-syntiant-tinyml

## Get more details and read the blog at:
https://44-2.de/syntiant-ndp-101-always-on-low-power-speech-recognition/
