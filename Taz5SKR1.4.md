## Lulzbot Taz 5 SKR 1.4 Turbo TMC2209 BLTouch TFT35

> [Marlin Fork Github Repository](https://github.com/jimbalny/Marlin-Taz-5-SKR-1.4-Turbo)

Replacing the Rambo board in the Taz 5 with the 32 bit SKR 1.4 Turbo.  

### Upgrade Details

I chose to replace the standard LCD screen with the TFT35 v3.0 as it has an excellent touch screen interface while still being able to switch back to the standard Marlin LCD menu by pressing and holding down the rotary encoder for a couple seconds. The TFT firmware is Open-Sourced by BigTreeTech and allows for much customization, icon themes, etc.  

The build isn't yet completed but the firmware fork I'm working on is linked below. I'll also share the hex files as well as the forked source for the TFT35 firmware to help you get up and running faster.  

**Current Progress:**

> - [x] Firmware modifications (Marlin 2.0.x)
> - [ ] Design new control box enclosure *(In Progress)*
> - [ ] Wiring and board replacement
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

![Enclosure Preview](https://jimbalny.github.io/images/TazSKR_preview.png)