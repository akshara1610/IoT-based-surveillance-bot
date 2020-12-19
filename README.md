# IoT-based-surveillance-bot
This is an IoT-based surveillance robot. It runs on a Raspberry Pi 3B, leverages the flask framework for generating control signals for the bot. Hardware used:

Raspberry Pi 3B
Picamera 5MP
2WD robot chassis with 4AA battery box and Bo motors
L239D Motor driver module
Power bank
Procedure:

Enable SSH, Camera, VNC on your Pi
Install motion library, set motion daemon to yes and set permission for the target directory.
Turn off localhost streaming
Start the motion service. Now the stream will be available on port 8081 of your Rasp Pi.
Install flask.
Create a directory called bot. Inside this, create a directory called templates.
Inside templates, save the html file as robot.html
Inside bot, save the python code as robot.py
Assemble the hardware.
Ensure that the Picam and Motors are working.
To execute, open terminal, cd to bot, type python bot.py
Now copy the url and paste it in your browser
