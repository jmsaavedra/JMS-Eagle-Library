[jos.ph](http://jos.ph) Eagle CAD Libraries
=================

[EagleCAD](https://cadsoft.io) library of parts and footprints I couldn't find anywhere else. Many of these are literally footprints with pinouts for integrating Adafruit breakout boards into your PCB.

__Note__: These have been created for various projects over the past few years, they are not the most consistent in terms of silk/labeling design. However, they are all proven unless marked otherwise.

# components #

### jos-ph.lbr

**[APA102C 5050 RGB LED](https://www.adafruit.com/products/2343)**

  + Adafruit DotStar Single LED Pixel
  + [Datasheet](https://cdn-shop.adafruit.com/product-files/2343/APA102C.pdf)

**[Adafruit Audio FX Sound Board + 2x2W Amp](https://www.adafruit.com/products/2210)**

  + Variants with and w/o speaker pins

**[Adafruit FONA 808](https://www.adafruit.com/product/2542)**

  + Mini Cellular GSM + GPS Breakout
  + [Product Overview](https://learn.adafruit.com/adafruit-fona-808-cellular-plus-gps-breakout/overview)

**[Adafruit HMC5883L Magnetometer](https://www.adafruit.com/products/1746)**

  + Triple-axis Compass Breakout
  + Variants with mounting drills and w/o

**[Adafruit PowerBoost 500 LiPo Charger Breakout](https://www.adafruit.com/products/1944)**

  + __UNPROVEN__

**[Adafruit TXB0104 Bi-Directional Level Shifter Breakout](https://www.adafruit.com/products/1875)**

  + [Datasheet](https://cdn-shop.adafruit.com/datasheets/txb0104.pdf)

**[Simblee](https://www.simblee.com) 7-pin DIP Breakout**

  + RF Digital Part Number: RFD77201
  + [Mouser Product](http://www.mouser.com/ProductDetail/RF-Digital-Wireless/RFD77201)

**NKK SPDT Switch**

  + Part Number: GW22LCP
  + [Datasheet](http://www.nkkswitches.com/pdf/GW.pdf)

---

### jmsaavedra.lbr

Older eagle library with parts from the past...

**1/8" / 3.5mm Stereo Audio Jack SMD**

  + Switchcraft manu part: 35RASMT4BHNTRX
  + Digikey part: SC1488-1-ND
  + [Datasheet](http://www.switchcraft.com/Drawings/35rasmt4bhntrx_cd.pdf)

**Single Pole OptoMOS Solid State Relay SMD**

  + IXYS manuf part: CPC1025N
  + Digikey part: CLA234CT-ND
  + [Datasheet](http://www.clare.com/home/pdfs.nsf/www/CPC1025N.pdf/$file/CPC1025N.pdf)


## Installation
_forked from instructions [here](https://github.com/adafruit/Adafruit-Eagle-Library)_

1. Download the .zip file of this repo.
2. Open Eagle and select the `Control Panel` window.
3. Choose `Options` and from the drop down that appears, `Directories`.
4. Change the Libraries line from: `$EAGLEDIR/lbr` to something like:
```
    $EAGLEDIR/lbr:$HOME/my_external_lbrs (for OS X)
    $EAGLEDIR\lbr;$HOME\my_external_lbrs (for Windows)
```
5. Click `OK` to save your changes.
6. Eagle will prompt to create the directory if it does not already exist. Note
the location and choose `Yes` to create the directory.

    OSX: `$HOME/my_external_lbrs` changes to: `/Users/mosfet/my_external_lbrs/`

    Windows: `$HOME\my_external_lbrs` changes to: `C:\Users\Mosfet\Documents\my_external_lbrs`

7. Find and open the `my_external_lbrs` folder. Unzip the downloaded file and drag `jos-ph.lbr` into the
   new `my_external_lbrs` folder.
8. Restart Eagle. The library should be now be usable.

