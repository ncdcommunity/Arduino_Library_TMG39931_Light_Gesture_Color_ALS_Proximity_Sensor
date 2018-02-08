[![TMG39931](TMG39931_I2C.png)](https://store.ncd.io/product/tmg39931-light-sensor-gesture-color-als-and-proximity-sensor-i2c-mini-module/)

# TMG39931

The TMG39931 features advanced gesture detection, proximity detection, digital ambient light sensor (ALS), Color Sensor (RGBC), and optical pattern generation/transmission.The slim modular package incorporates an IR LED and factory calibrated LED driver.
This Device is available from www.ncd.io 

[SKU: TMG39931_I2CS]

(https://store.ncd.io/product/tmg39931-light-sensor-gesture-color-als-and-proximity-sensor-i2c-mini-module/)
This Sample code can be used with Arduino.

Hardware needed to interface TMG39931 sensor with Arduino

1. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-nano/">Arduino Nano</a>

2. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-micro-with-i2c-expansion-port/">Arduino Micro</a>

3. <a href="https://store.ncd.io/product/i2c-shield-for-arduino-uno/">Arduino uno</a>

4. <a href="https://store.ncd.io/product/dual-i2c-shield-for-arduino-due-with-modular-communications-interface/">Arduino Due</a>

5. <a href="https://store.ncd.io/product/tmg39931-light-sensor-gesture-color-als-and-proximity-sensor-i2c-mini-module/">TMG39931 Light Sensor Gesture, Color,ALS and Proximity Sensor</a>

6. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

TMG39931:

The TMG39931 features advanced gesture detection, proximity detection, digital ambient light sensor (ALS), Color Sensor (RGBC), and optical pattern generation/transmission.The slim modular package incorporates an IR LED and factory calibrated LED driver.

Applications:

• Gesture Detection

• Color Sense

• Ambient Light Sensing

• Cell Phone Touch Screen Disable

• Mechanical Switch Replacement

• Printed Bar Code Emulation 

How to Use the TMG39931 Arduino Library

The TMG39931 has a number of settings, which can be configured based on user requirements.
          
1.Accessing time setting:The following command is used to set the accessing time of TMG39931 sensor.

            tmg.setATime(ATIME_712MS);                  // Cycles: 256, Time: 712 ms Max Count: 65535
             
2.Wait time:The following command is used to set the wait time for sensor.

            tmg.setWTime(WTIME_1);                      // Wait Time: 1, Time (WLONG = 0): 2.78 ms Time (WLONG = 1):  0.03 sec
           
3.Proximity drive:The following command is used to set the proximity drive.

             tmg.setProximityDrive(PDRIVE_100);          // LED Strength – PDL=0: 100%
           
4.Proximity gain setting:The following command is used to set the gain of proximity..             
           
             tmg.setProximityGain(PGAIN_1X);             // Proximity Gain: 1X
            
5.Color gain setting:The following command is used to set the gain of color.         

             tmg.setColorGain(AGAIN_1X);                 // Color Gain: 1X
             

