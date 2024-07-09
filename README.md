# SM_Week-3_Task-2
SM_Week 3_Task 2



esp32-with-sensors



In this project, esp32 is being used along with other sensors just as required.
For this task I used WOKWI and TinkerCAD, because WOKWI doesnt have a PIR Region feature as TinkerCAD. So, TinkerCAD uses Arduino but the concept still applies. You may want to start watching my WOKWI project then watch my TinkerCAD project to understand accurately how the PIR Region works.

The esp32 here is applied as an Alarm Trigger by detecting motion using PIR sensor + buzzer (to make sounds) + LED (to indicate emergency lights)
The explanation of the code will be in the same file that has The Code. And the explanation of the circuit will be inside the circuit diagram image.

Explanation:
Whenever someone enters the region of PIR, gets fetected by PIR, then, the esp32 gets a signal from PIR, the esp32 immediately sends specific signals to the buzzer and LED to memic an ALARM. When the detected person leaves the PIR Region, seconds later, the esp32 sends signals to shut down the ALARM.

This application is useful when integrating it with IoT to create a system for whenver unauthorized person enters home, room, building, etc.. the owner will be notified.


