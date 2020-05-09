# My KiCAD libraries

This repo contains KiCAD models and footprints I made for various components.
It may or may not grow in the future.

## Omron relays
This repo contains a footprint for __Omron LY1* and LY2*__ relays.
It has been succefully tested with LY2N-J (also written LY2NJ) relays.
According to [Omron's datasheet](https://www.fa.omron.com.cn/data_pdf/cat/ly_ds_e_4_7_csm54.pdf?id=949), it should also suit the following parts:

* LY1
* LY1N
* LY1-D
* LY1N-D2
* LY2
* LY2Z
* LY2N
* LY2-D
* LY2Z-D
* LY2N-D2
* LY2ZN-D2

This repo only contains the **footprint** of such parts. To add the component to a **schematic**, choose any component that has the same number of terminals. For instance, choose from the built-in `relays` library, or, slightly better, the `LY20` component from the `relay` library from library.oshec.org.

Then, associate these parts to this footprint.

![Screenshot of the Omron LY-2x footprint](images/omron-LY2.png)

## Omron mini-USB connector
This repo contains a footprint for the __Omron XM7D-0512__ through-hole mini-USB connector. It comes from [https://www.snapeda.com/parts/XM7D-0512/Omron%20Electronics%20Inc-EMC%20Div/view-part/](https://www.snapeda.com/parts/XM7D-0512/Omron%20Electronics%20Inc-EMC%20Div/view-part/), but corrects how the edges are drawn (they were mostly drawn on the wrong layers from this original URL).

This is the footprint only. Any mini-USB connector symbol from the standard KiCad library will do (although the original URL for the footprint also contains a symbol, that should be OK).

![Screenshot of the Omron XM7D-0512 footprint](images/omron-XM7D-0512.png)

## More to come
(maybe)