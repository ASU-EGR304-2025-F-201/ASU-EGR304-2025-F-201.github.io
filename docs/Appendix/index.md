---
title: Appendix - Main Page
---

Located in the links below are two videos demonstrating our team's ability to send data between subsystems. 

# Light Sensor
The light sensor connects to the speaker, sending a high signal while the sensor (plant) is receiving adequate light, keeping the speaker off. When the sensor is not receiving enough light, a low signal gets sent, and the speaker sounds.

# Speaker
The speaker subsystem receives input from both the light sensor and the moisture sensor. The speaker will sound with a particular tone if it receives a low signal from the light sensor, and a different tone if the signal from the moisture sensor stops. These different tones will prompt the user to either move the plant to more sunlight or to check the moisture sensor.

# Motor
The motor will control the pump to irrigate the plants. When the motor receives a high signal from the moisture sensor, it will rotate to irrigate the plant. When the motor receives a low signal from the moisture sensor, it will rotate in the opposite direction, stopping the flow of water.

# Moisture Sensor
In the video, the moisture sensor simulates drying soil. When the soil reaches a critical moisture threshold, it sends a high signal to the motor to turn it on. While this happens, a constant high status signal is sent to the speaker board as proof of life of the moisture sensor. If the moisture sensor breaks, the speaker will sound.

# Videos
The two videos demonstrating the testing are below. Please click the thumbnails to watch the videos hosted on YouTube

[![YouTube Video 1](https://img.youtube.com/vi/C-wd-mp8sfM/maxresdefault.jpg)](https://www.youtube.com/watch?v=C-wd-mp8sfM)

[![YouTube Video 2](https://img.youtube.com/vi/AnvqiU68s2Q/maxresdefault.jpg)](https://www.youtube.com/watch?v=AnvqiU68s2Q)
