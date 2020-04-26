# WatchFace-BIP-SimpleWhiteDigital
My Simple White Digital (red minutes) Amazfit BIP Watch Face.  Attempted to produce a clean, basic and elegant digital watch face with minimal clutter. No status (other than small battery pips to indicate battery state at the bottom of the face), activity or weather icons.  This one is slightly complicated because of the text month names.

Derived from https://amazfitwatchfaces.com/bip/view/28703

## Workflow

https://amazfitwatchfaces.com/bip/top is a great place to start for ideas and resources such as icons, number and graphics.

I use watchface editor…
https://forum.gizchina.it/index.php?/topic/1489-bip-wf-editor-by-ilgruppotester/

It’s a utility written in compiled Python (into pyd files) by this guy…
https://github.com/lucventurini

You can grab a face you kinda like off amazfitwatchfaces and decompile it using this…
https://bitbucket.org/valeronm/amazfitbiptools/downloads/  (plugs into the watch editor).  The layout is controlled with a json script.

Customise it and rebuild it.  Then use AmazTools to load the bin file onto the watch from the iPhone…
https://apps.apple.com/us/app/amaztools/id1386033880

176x176 pixels with an 8-colour palette. The decompiler seems to do the dithering on images if you aren’t using one of the 8 colours. ![Colour pallete](https://github.com/threadz/WatchFace-BIP-RoundDial/blob/master/Resources/AmazfitBIPColourPallette.jpg )

## Releases

|                                                                             Face                                                                            | Version | Description                                                                                                                                                                  |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|:-------:|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![Watchface ](https://github.com/threadz/WatchFace-BIP-SimpleWhiteDigital/blob/master/Releases/SimpleWhiteDigital_24h_packed_animated_V1.0.gif ) |   [1.0](https://github.com/threadz/WatchFace-BIP-RoundDial/blob/master/Releases/SimpleWhiteDigital_24h_packed_V1.0.bin)   | Basic white digital with red minutes. Only battery status at the bottom of the face. icons.                                                                                                                |
| ![Watchface ](https://github.com/threadz/WatchFace-BIP-SimpleWhiteDigital/blob/master/Releases/SimpleWhiteDigital_24h_packed_animated_V2.0.gif ) |   [2.0](https://github.com/threadz/WatchFace-BIP-RoundDial/blob/master/Releases/SimpleWhiteDigital_24h_packed_V2.0.bin)   | Enlarged hours and minutes.                                                                                                                |
| ![Watchface ](https://github.com/threadz/WatchFace-BIP-SimpleWhiteDigital/blob/master/Releases/SimpleWhiteDigital_24h_packed_animated_V2.1.gif ) |   [2.1](https://github.com/threadz/WatchFace-BIP-RoundDial/blob/master/Releases/SimpleWhiteDigital_24h_packed_V2.1.bin)   | Vertical battery indicator.                                                                                                                |  
