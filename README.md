# Mack-e-OzInverter

A Nano based PWM Inverter based on the Nano OzInverter.

![](https://github.com/mackelec/Mack-e-OzInverter/blob/master/images/Mack-e-OzInverter_201907_overlay_50.png)


This controller is base on the ideas of the OzInverter often featured on the [BackShed Forum](https://www.thebackshed.com/forum/forum_topics.asp?FID=4) and the Nano code is modified from Poida's Nano inverter Code.

This controller plugs directly into my Full-Bridge-Driver board that I use in my  WarpVerter project
 -  [Full-Bridge-Driver board](https://github.com/mackelec/StepInverter/tree/master/PCB/Driver_Boards#full-bridge-driver-board-201907)
 
 ### Features
 
  -  Open loop control of output voltage based on input (Battery) voltage on 50Hz update.  This differs to Poida's code where he uses closed loop control based on feedback of the AC output, on a 100hz basis.  Regulation may not track quite as well but it is simpler.
  
  -  Forms part of a modular Inverter design, plugs into my Driver board, which then plugs into as many driver boards and Mosfet boards as desired.
  
  -  Individual Momentary Inputs for ON and OFF.
  -  Bi colour LED to show Run status.
