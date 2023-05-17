# Remote IT

Remote IT is a series of solutions for modern problems

**This project is only meant for memes and jokes, and is not meant for any malicious activities. We take no legal responsibility for any damage caused by them.**

## Why
Remote IT was developed as a project for a grade 12 computer science class by two guys.
The first concepts was a way to access computers without having control of computer ports and/or port forwarding, but as time went on, it became a full solution with both hardware and software involved

## How
Remote IT consists of two parts:
- C&D - A series of arduino programs and a sick piece of hardware to download things
- ROT - Remote operating toaster

### [C&D](https://github.com/notHackers/arduino)
C&D is a solution to a surprising amount of 'problems'
It consists of an Arduino Leonardo clone, an SD card reader, and some other bits and bobs to make it more functional.
See [this](C&D) for more.
![](https://lh3.googleusercontent.com/CWSZCvjOvp3raG0yF6XeT9lMUMgN93Qm2GI2n2o93oCgjTXFbJxCbUyHnW9byMG6g8XQF0cLKxZeMMiKJWJs3XZ_V-E2c9bb5tJmMN8s4K7F7ndgUiH2AbsCNkLB_ppZd429RqNyCMx8iHMirLpvXCBAGg=s2048)
![](https://lh3.googleusercontent.com/lh-y49nfOBJRSWrGP48lQuRaHMS8ZlyzDeOmxupuP-vfbBSBmvFDgLjx06EcPPQIWe_Jh-I1LIBkrwIXISUzmiG0PaFmUwUQAaVR9Lyx8I2z-WwGiLX3W5iAnWQZqtCX3Vx5ZRFhALyN8sbfEkgwO0XK-A=s2048)

### [ROT](https://github.com/notHackers/rot)
ROT is a set of 3 1/2 progams:
- Frontend - A react app built to  view things nicely, it kinda sucks, I'm not a frontend dev
- Server - A HTTP REST server that handles things, actually, everything
- Installer/Client :
	- The installer installs the client
	- The client connects to the server through REST requests
![](https://lh6.googleusercontent.com/dRzAbrF8qJS3B9qHRdK0QCs-fBicgNSC_ZURXBZiwlR9tOSDxCRKwbQ8qdusOQU9tIghuE9MgQAbfclXH6kBb3H05vOT_ySeawsWEcjadDU7dKDrFQcV3RbdDkDC-l5qlQGzOALb_PbTX1Pmzq-gT39jBQ=s2048)
![](Pasted image 20230516231008.png)
See [this](https://github.com/notHackers/rot) for more info
## How to use it

1. Have an arduino capable of serial communication, preferably one with  direct serial control (not  an UNO)
2. Check out the image, no, I will give a schematic
3. choose the program you want to download and the script that relates to it
4. upload the arduino program and put the program to be injected onto the SD card
5. Plug it and run it!
