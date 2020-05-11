## Lulzbot Taz 5 SKR 1.4 Turbo TMC2209 BLTouch TFT35

*Replacing the Rambo board in the Taz 5 with the 32 bit SKR 1.4 Turbo.*

> [Marlin Fork Github Repository](https://github.com/jimbalny/Marlin-Taz-5-SKR-1.4-Turbo)
> [STL Files at Thingiverse](https://www.thingiverse.com/thing:4354523)

### Upgrade Details

I chose to replace the standard LCD screen with the TFT35 v3.0 as it has an excellent touch screen interface while still being able to switch back to the standard Marlin LCD menu by pressing and holding down the rotary encoder for a couple seconds. The TFT firmware is Open-Sourced by BigTreeTech and allows for much customization, icon themes, etc.  

The build isn't yet completed but the firmware fork I'm working on is linked below. I'll also share the hex files as well as the forked source for the TFT35 firmware to help you get up and running faster.  

**Current Progress:**

> - [x] Firmware modifications *(Marlin 2.0.x)*
> - [x] Design new control box enclosure *(Printed / Tested OK)*
> - [ ] Wiring and board replacement *(In Progress)*
> - [ ] Test and first prints  
  
  

### Parts Purchase Links

- [SKR 1.4 Turbo with TMC2209](https://www.amazon.com/BIGTREETECH-Printer-Control-Smoothieboard-Upgrade/dp/B082YTZJS2/)  
- [TFT35 v3.0](https://www.amazon.com/BIGTREETECH-Display-Controller-Compatible-Printer/dp/B07W1PB11F)  
- [ANTCLABS BLTouch](https://www.amazon.com/ANTCLABS-BLTouch-Leveling-Premium-Extension/dp/B01FFV2TOS/)  


### Tools and Misc Parts

- [IWiss JST Crimper](https://www.amazon.com/gp/product/B019ARWWFY/) (To change to standard RAMPS-style connectors)  
- [All the JST XHP Crimps you'll need](https://www.amazon.com/gp/product/B015Y6JOUG)  
- [IDC Connectors and Crimp Tool](https://www.amazon.com/gp/product/B07WHFWMYQ/)  
- [10-pin Ribbon Cable](https://www.amazon.com/gp/product/B07P77YRB2) (Needed to extend short LCD Cable)  

### Optional Tools and Misc

**For going above and beyond for shielding cables:**  

- Copper Adhesive Tape (To shield LCD Cables)
- 3/4" (or 20mm) x 48" Heatshrink (To shield LCD Cables)
- 22AWG or 26AWG Green Hookup Wire (Shielding)

**For getting the 24v Heated Bed off the SKR's Mosfet:**  

- [Auber 100A DC-DC SSR Low On-Resistance](https://www.auberins.com/index.php?main_page=product_info&products_id=288)  
    - ![SSR](https://jimbalny.github.io/images/SSR.jpg)  
- [Auber External-Mount Heat Sink for 25A SSR](https://www.auberins.com/index.php?main_page=product_info&cPath=2_48&products_id=244)
    - ![SSR Heatsink](https://jimbalny.github.io/images/Heatsink.jpg)  


### Firmware

- [Marlin Taz 5 SKR 1.4 Firmware Fork](https://github.com/jimbalny/Marlin-Taz-5-SKR-1.4-Turbo)
- [BTT TFT 35 v3.0 Firmware](https://github.com/bigtreetech/BIGTREETECH-TouchScreenFirmware)  

### Titan Aero Upgrade

I chose the "mirrored" version for the conveniance of having the tension adjustment in front and the stepper motor on the right like the standard hexagon hotend.

- [E3D Titan Aero Mirrored 3mm 24v](https://www.matterhackers.com/store/l/e3d-titan-aero-extruder-24v-300mm-mirrored/sk/M1HPS73T)  
- [ITWorks E3D Titan Aero Mirrored STL Files](https://www.thingiverse.com/thing:2680398)  
- [Basic Titan Aero BLTouch Moiunt](https://www.thingiverse.com/thing:3127511)  

Optional:

- [E3D Volcano Eruption Pack](https://www.matterhackers.com/store/l/e3d-volcano-eruption-pack-300mm-24v/sk/MWFWKV5P)  
- [Volcano Eruption Pack from China](https://www.aliexpress.com/item/32924003172.html?spm=a2g0s.9042311.0.0.e2244c4d3Qny0h) (What I'm using)  



**Enclosure Preview:**

![Enclosure Preview](https://jimbalny.github.io/images/TazSKR1.4.png)
![Enclosure Inside](https://jimbalny.github.io/images/TazSKR_inside.png)