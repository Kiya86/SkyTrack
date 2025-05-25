title: "SkyTrack"
author: "Kiya Kesheh"
description: "100 mph FPV drone!
created_at: "2025-05-21"

## **Day 1** (05/21/2025)

* Did research on what components are best  
  * Compared thrust, KV, and RMP curves for multiple 5-inch prop motors   
  * Selected the:  
    *  Axisflying Bando 2207.5 1960 KV motors based on their torque and top-end RPM on 6 S  
  * Also chose a 65A 4 in 1 ESC for the motors  
    * 3065 AM32 65 A 4-in-1 ESC  
  * Compared flight controllers to see what is best and whether I should use F7 flight computers, but instead opted to use the F4 flight computer  
    * Matek F405-HDTE  
      * Has an STM32F405  
      * MPU6000  
      * Onboard OSD  
      * And built a current sensor   
  * Also did research on what propeller size I should be using and decided a 5-inch is best for a high-speed drone, so I chose:  
    * HQProp Ethix S4 5×4.5×3 tri-blades  
  * Also decided to use a 6S battery as the motors would run at max speed with it  
    * 2pcs CNHL Lipo Battery 6S 22.2V 1100mAh 1500mah 100C With XT60 For RC FPV Quadcopter Airplane Helicopter Hobby  
    *   
* Lastly made a BOM of all parts to see how much it would cost, and the exact price with tax and shipping is **$304.20**

## **Day 2** (05/22/2025)

* Made a sketch of a frame to work with the 5-inch props and made sure the center of gravity would not be messed up   
* Drew the sketch in Fusion 360 and made a 240mm diameter motor-to-motor spacing  
* Modeled the body with channels to route wires going from the ESC to the motors   
* Added other channels to hide wires   
* Added a low-profile canopy   
* Did not add mounting holes, as I will be using a soldering iron with brass inserts   
* Beefed up sections under high loads

## **Day 3** (05/23/2025)

* Fixed some geometry of the drone and reduced weight  
* Added more channels for battery wires  
* Started to make the GitHub repository (This was done a little later the day after (I might or might not have feel asleep))
* Added all parts to an Excel sheet and saw how much tax and shipping fees were on Aliexpress  
* Added everything to the BOM and finalized last-minute changes  
* 3D printed the frame with carbon reinforced filament (Nozzle is cooked)   
* The frame was printed at:  
  * Nozzle: 230 °C  
  * Bed: 100 °C  
  * Infill: Gyroid at 50% infill   
  * 0.2mm layers   
  * Speed: 75%   
  * Slicer: Cura

