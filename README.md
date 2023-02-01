# :rainbow: Color Blind LUTs

Lookup tables (LUTs) for [Fiji](https://fiji.sc/)/[ImageJ](https://imagej.github.io/) unambiguous to color blind humans.

## Background

**Masataka Okabe** and **Kei Ito** first proposed this color set in their meticulous article from 2002 describing how to make color blind friendly figures [1].
Using the LUT Panel plugin developed by **Patrick Pirrotte** and **Jerome Mutterer** [2], I created the corresponding LUT files for Okabe & Ito’s color set to use on confocal stacks in ImageJ.

**References:**

1. Okabe M, Ito K. **How to make figures and presentations that are friendly to color blind people**. In: Jfly: data repository for *Drosophila* researchers [Internet]. 20 Nov 2002 [cited 6 Apr 2015]. Available: https://jfly.uni-koeln.de/html/color_blind/ (or [PDF](https://jfly.uni-koeln.de/html/manuals/pdf/color_blind.pdf))
2. Pirrotte P, Mutterer J. **LUT Panel**. In: ImageJ plugins website [Internet]. 15 Mar 2003 [cited 6 Apr 2015]. Available: https://imagej.nih.gov/ij/plugins/lut-panel.html

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

## Install

**ColorBlindLUTs** is available in the list of Fiji update sites. To install simply:

1. Open Fiji and go to `Help` > `Update...` > `Manage update sites`
2. Scroll down and mark the checkbox for `ColorBlindLUTs`
3. Click `Close` and then `Apply changes` to install
4. Restart Fiji

The LUTs will appear in the `LUT Menu` as:

```
CB_Blue
CB_BluishGreen
CB_Orange
CB_ReddishPurple
CB_SkyBlue
CB_Vermilion
CB_Yellow
```

