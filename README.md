# Mack-e-OzInverter

A Nano based PWM Inverter based on the Nano OzInverter.

![](https://github.com/mackelec/Mack-e-OzInverter/blob/master/images/Mack-e-OzInverter_201907_overlay_50.png)


This controller is base on the ideas od the OzInverter often featured on the [BackShed Forum](https://www.thebackshed.com/forum/forum_topics.asp?FID=4) and the Nano code is modified from Poida's Nano inverter Code.

This controller plugs directly into my Full-Bridge-Driver board that I use in my  WarpVerter project
 -  [Full-Bridge-Driver board](https://github.com/mackelec/StepInverter/tree/master/PCB/Driver_Boards#full-bridge-driver-board-201907)
 
 ### Features
 
  -  Open loop control of output voltage based on input voltage on 50Hz update.  This differs to Poida's code where he uses closed loop control based on feedback of the AC output, on a 100hz basis.  Regulation may not track quite so well but it is simpler and possibly more reliable.
  
  -  Very modular, plugs into my Driver board, which then plugs into as many driver boards and Mosfet boards as desired.
  
  -  
