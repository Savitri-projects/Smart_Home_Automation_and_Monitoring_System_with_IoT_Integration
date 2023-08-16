
# Smart Home Automation and Monitoring System with IoT Integration

This project aims to craft a simulation of an IoT-enabled Smart home with automated features and real-time monitoring. The system employs PIR and distance sensors for hands-free door control, activates fans and LEDs when occupants are present, adjusts lighting based on ambient brightness, alerts against hazardous gases, and uses ThingSpeak for remote tracking of temperature, light, and gas levels. A holistic integration for modern living in its real hardware implementation is the idea.


## How to use
1. Login/sign up to Tinkercad from https://tinkercad.com/

2. There is a .brd file uploaded, try opening it in the Tinkercad, otherwise: https://www.tinkercad.com/things/gBijXVQUKkE - open this link and please **"copy and tinker"**

3. Login into ThingSpeak (it is an IoT analytics platform service) from https://thingspeak.com/ with your MATLAB account/create a new one. 

4. Select channels in ThingSpeak. Create a new channel

5. Name it with which ever name you want.
6. But make sure to give the fields in the following way:

![App Screenshot](https://i.postimg.cc/155GtGk4/image.png)

7. Save the channel and go to API keys tab and find a 16 character **"Write API Key"** and copy it
8. Now open Tinkercad and find the 15th line ![App Screenshot](https://i.postimg.cc/sXJv5LkS/image.png)
9. Add the copied key from ThingSpeak in the place of XXXXXXXXXXXXXXXX
10. And that's all!!!






## How to check and what to check

Now that you have setup everything, you can vary the temperature, brightness and distance of the gas from the gas sensor and see the values plotted in a graph in ThingSpeak

![App Screenshot](https://i.postimg.cc/sxmGR2sv/Smart-Home-Automation-and-Monitoring-System-with-Io-T-Integration.png)

Start the simulation.

1. Adjust the temperature by moving the bar (pointed in the picture)
![App Screenshot](https://i.postimg.cc/L8JXXDm9/image.png) and observer the third graph in ThingSpeak
![App Screenshot](https://i.postimg.cc/vTRnbKJ6/image.png)

2. Change the distance between gas and the gas sensor (as shown in the picture)
![App Screenshot](https://i.postimg.cc/L4fCLF6w/image.png) and observe the second graph in ThingSpeak
![App Screenshot](https://i.postimg.cc/0QC61N0h/image.png)You can also see the alarm ringing when the gas sensor recognizes gas

3. Change the brightness by moving the bar of the photo resistor (as shown in the picture)
![App Screenshot](https://i.postimg.cc/1z3RVKG7/image.png) and observer the first graph in ThingSpeak
![App Screenshot](https://i.postimg.cc/7Zmw4TF3/image.png)You can also see the bulb in the circuit going off when the brightness is maximum

4. A PIR sensor is present, allowing you to adjust the distance, which detects a person's entry or exit from the room, thereby triggering the activation and deactivation of the bulb and fan. Additionally, a "Micro Servo" motor is incorporated that rotates when someone is in close proximity to the door, facilitating its opening and subsequent closure after a brief duration.

![App Screenshot](https://i.postimg.cc/QCCjYgNY/image.png)