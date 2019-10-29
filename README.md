# Video Doorbell, Lab 7

*A lab report by Christine Ku*

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**
https://youtu.be/GqEdaA8Gjpc

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**
The elements that were used to enable the web camera include setting up the web server, the webcam set up to define how and which camera to use, the serial communication with the Arduino, and the communication with the web browser and Arduino for the buttons and LEDs.

**b. Include a video of your working video doorbell**

https://youtu.be/hLQdzGtDyQo

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**
I tried several libraries to try and do face recognition, send email and text notifications, and modifying the image. The email packages usually needed me to establish a host and modify other properties, but I couldn't get the right settings to work. For the text notifications, a lot of the packages actually needed a separate account for the services. Ultimately, a lot of the packages that I tried to use were deprecated or had errors in them so I ended up using an image-to-ascii package. It doesn't look as defined as their examples though because there wasn't much contrast in the photo caputred by the webcam.

**b. Upload a video of your working modified project**
https://youtu.be/AG3tBIabJKc
