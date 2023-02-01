# :rainbow: Color Blind LUTs

Lookup tables (LUTs) for [Fiji](https://fiji.sc/)/[ImageJ](https://imagej.github.io/) unambiguous to color blind humans.

## Background

**Masataka Okabe** and **Kei Ito** first proposed this color set in their meticulous article from 2002 describing how to make color blind friendly figures [1].
Using the [LUT Panel](http://rsb.info.nih.gov/ij/plugins/lut-panel.html) plugin developed by **Patrick Pirrotte** and **Jerome Mutterer**, I created the corresponding LUT files for Okabe & Ito’s color set to use them on confocal stacks in ImageJ.

[1] Okabe M, Ito K. **How to make figures and presentations that are friendly to color blind people**. In: Jfly: data repository for *Drosophila* researchers [Internet]. 20 Nov 2002 [cited 6 Apr 2015]. Available: https://jfly.uni-koeln.de/html/color_blind/ (or [PDF](https://jfly.uni-koeln.de/html/manuals/pdf/color_blind.pdf))

## Color set

![](ColorBlindLUTs.png)

| Name           | HEX    | RGB         | CMYK       |
| -------------- | ------ | ----------- | ---------- |
| Black          | 000000 | 0,0,0       | 0,0,0,100  |
| Blue           | 0072b2 | 0,114,178   | 100,50,0,0 |
| Sky Blue       | 56b4e9 | 86,180,233  | 80,0,0,0   |
| Bluish Green   | 009966 | 0,153,102   | 97,0,75,0  |
| Yellow         | f0e442 | 240,228,66  | 10,5,90,0  |
| Orange         | e69f03 | 230,159,0   | 0,50,100,0 |
| Vermilion      | d55e00 | 213,94,0    | 0,80,100,0 |
| Reddish Purple | cc79a7 | 204,121,167 | 10,70,0,0  |

## Installation

### Automatic install/updates (recommended)

1. Open Fiji and click on `Help` > `Update...` > `Manage update sites`
2. Click on `Add update site`, a new line will appear at the bottom of the list
3. Add `https://sites.imagej.net/ColorBlindLUTs/` to the **URL** field
4. Add `ColorBlindLUTs` to the **Name** field
5. Click `Close` to close the list
6. Click `Apply changes` to install
7. Restart Fiji

### Manual install

1. Clone or download this repository to your computer
2. Copy `.lut` files to the `luts` directory in your Fiji installation
3. Restart Fiji
4. CB LUTs will be accessible in the LUT Menu

