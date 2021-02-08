EMBEDDED SYSTEM PROGRAMMING / ARDUINO PROJECT 

Elmas Başak Gören
	Project Aim

The purpose of this project is to create a clock using TIMER interrupts with 12 and 24 hour alternating settings. It is also to make a general alarm adaptation for the clock by creating individual alarms for the 12-hour part and for the 24-hour part. It is also one of the features of this project to show the temperature on the lcd by creating a simple temperature for the system. This project was done using the Tinkercad platform and no extarnel library was used except for the use of Lcd.
	Metarials And Code

There are 4 main functions in the project. These include setting PM/AM, on/off for alarm, the alarm time and finally measuring the temperature in the circuit. The Timer system was used while the clock part was being done in the project. This system actually meant using the clock system, which is also OCR1A. This system was set with OCR1A = 15624; for this reason it did not match our present second. 4 buttons 3 sliders were used. To summarize our purpose, the buttons were used to set the alarm time, set the alarm minute, adjust the degree change (fahrenheit, celcius) and snooze the alarm. Sliders were used to turn the alarm on and off, to set the AM/PM setting on the alarm, and to switch the 12 and 24 hours. The 12% mode was taken for 12 hours clock part and 24% mode was taken for 24 hours clock part. Also two separate functions were written in the code for these parts. There were 3 pin activity at the beginning of the code. The implementation of these pins was done in digitalRead (pinX) = HIGH). 2 different mathematical operations were performed for temperature measurement. float temp = ((analogRead(pinTemp) * (5.0/1024))-0.5 )/0.01 it was used for celcius. For Fahrenheit, the celcius was converted. The potentiometer was used to regulate the circuit's electricity.
 
TinkerCad Link: https://www.tinkercad.com/things/2tbL0p6dwnK-deneme-led/editel?sharecode=2vTCsGEggtgJKhJukk8GYqFHBKOMvKC_Q1B3MsynCmA
