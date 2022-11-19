# :rainbow: Color Blind LUTs

Set of lookup tables (LUTs) for [Fiji](https://fiji.sc/)/[ImageJ](https://imagej.github.io/) with colors unambiguous to color blind humans.

## Color set

| Name           | HEX    | RGB         | CMYK       |
| -------------- | ------ | ----------- | ---------- |
| Black          | 000000 | 0,0,0       | 0,0,0,100  |
| Orange         | e69f03 | 230,159,0   | 0,50,100,0 |
| Sky Blue       | 56b4e9 | 86,180,233  | 80,0,0,0   |
| Bluish Green   | 009966 | 0,153,102   | 97,0,75,0  |
| Yellow         | f0e442 | 240,228,66  | 10,5,90,0  |
| Blue           | 0072b2 | 0,114,178   | 100,50,0,0 |
| Vermilion      | d55e00 | 213,94,0    | 0,80,100,0 |
| Reddish Purple | cc79a7 | 204,121,167 | 10,70,0,0  |

**Masataka Okabe** and **Kei Ito** proposed this set of color blind safe colors in their meticulous report entitled:

Okabe M, Ito K. **How to make figures and presentations that are friendly to color blind people**. In: Jfly: data repository for *Drosophila* researchers [Internet]. 20 Nov 2002 [cited 6 Apr 2015]. Available: https://jfly.uni-koeln.de/html/color_blind/ (or [PDF](https://jfly.uni-koeln.de/html/manuals/pdf/color_blind.pdf))

I generated the LUT files generated using the [LUT Panel](http://rsb.info.nih.gov/ij/plugins/lut-panel.html) ([source](http://rsb.info.nih.gov/ij/plugins/lut-panel.html)) ImageJ plugin developed by **Patrick Pirrotte** and **Jerome Mutterer**.

## Installation

1. Clone or download this repository to your computer
2. Copy `.lut` files to the `luts` directory in your Fiji installation
3. Restart Fiji
4. CB LUTs will be accessible in the LUT Menu

