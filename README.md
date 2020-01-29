# RFID-Based-Attendance-System-using-Arduino
RFID Based Attendance System using Arduino and RFID MFRC522 Module.

# Why did we decide to make it?
Attendance in University is generally paper based which may sometimes cause errors. Taking attendance manually consumes more time. So, In this project we have designed RFID Based Attendance System using Arduino and RFID MFRC522 Module. In this system, each student is issued an RFID card as their id card and their attendance is marked when they touch their card to RFID reader.

# What is RFID?
RFID stands for Radio Frequency Identification.Here digital data stored in RFID tags are captured by a reader via radio waves.

# Components we used in the project
1.Arduino Uno Board

2.RFID MRFC522 module

3.SD card module

4.RTC module

5.LCD display (20*4) with i2c lcd module

# Components Connect With Arduino UNO

1) RFID MFRC522
---------------

Pin   |    Wiring to Arduino Uno
--------------------------------
SDA   |    Digital 10
--------------------------------
SCK   |    Digital 13
--------------------------------
MOSI  |    Digital 11
--------------------------------
MISO  |    Digital 12
--------------------------------
IRQ   |    unconnected
--------------------------------
GND   |    GND
--------------------------------
RST   |    Digital 9
--------------------------------
3.3V  |    3.3V
--------------------------------

Caution: You must power this device to 3.3V!


2) Real Time Clock (RTC) Module (DS1307 and DS3231)
--------------------------------------------------

Pin    |   Wiring to Arduino Uno
--------------------------------
SCL    |   A5
--------------------------------
SDA    |   A4
--------------------------------
VCC    |   5V
--------------------------------
GND    |   GND
--------------------------------

If you’re using other Arduino board rather than the uno, chek out what are their SCL and SDA pins.

    Nano: SDA (A4); SCL(A5)
    MEGA: SDA (20); SCL(21)
    Leonardo: SDA (20); SCL(21)

3) SD Card module
-----------------

SD card module  |   Wiring to Arduino Uno
---------------------------------------------------------
VCC             |   3.3V or 5V (check module’s datasheet)
---------------------------------------------------------
CS              |   4
---------------------------------------------------------
MOSI            |   11
---------------------------------------------------------
CLK             |   13
---------------------------------------------------------
MISO            |   12
---------------------------------------------------------
GND             |   GND
---------------------------------------------------------

4) I2C module
-------------

I2C Character LCD |  Arduino
----------------------------
GND         	  |  GND
----------------------------
VCC        	  |  5 V
----------------------------
SDA        	  |  A4
----------------------------
SDL         	  |  A5
----------------------------


# check out our project at : https://create.arduino.cc/projecthub/team_chkr/rfid-based-smart-attendance-system-46b045?ref=user&ref_id=1435285&offset=0
