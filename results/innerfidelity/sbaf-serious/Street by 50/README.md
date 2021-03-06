# Street by 50

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.9dB
GraphicEQ: 10 -84; 20 1.1; 22 0.3; 23 -0.1; 25 -0.8; 26 -1.2; 28 -1.9; 30 -2.6; 32 -3.2; 35 -4.0; 37 -4.5; 40 -5.2; 42 -5.6; 45 -6.2; 49 -6.9; 52 -7.4; 56 -7.9; 59 -8.3; 64 -8.8; 68 -9.1; 73 -9.5; 78 -9.8; 83 -10.1; 89 -10.4; 95 -10.6; 102 -10.7; 109 -10.8; 117 -10.8; 125 -10.8; 134 -10.8; 143 -10.7; 153 -10.6; 164 -10.4; 175 -10.0; 188 -9.7; 201 -9.3; 215 -8.7; 230 -8.9; 246 -9.9; 263 -9.7; 282 -9.1; 301 -8.6; 323 -8.2; 345 -7.5; 369 -7.1; 395 -6.9; 423 -6.5; 452 -6.3; 484 -6.0; 518 -5.1; 554 -3.0; 593 -0.1; 635 1.2; 679 2.2; 726 2.7; 777 2.4; 832 1.5; 890 0.7; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.9; 1248 -0.9; 1336 -0.2; 1429 0.6; 1529 -0.2; 1636 -1.7; 1751 -3.0; 1873 -4.0; 2004 -4.9; 2145 -5.6; 2295 -5.8; 2455 -5.8; 2627 -5.5; 2811 -5.0; 3008 -4.3; 3219 -3.6; 3444 -2.2; 3685 -1.1; 3943 0.4; 4219 1.7; 4514 4.3; 4830 5.7; 5168 5.2; 5530 0.9; 5917 -0.7; 6331 2.8; 6775 3.7; 7249 1.0; 7756 0.3; 8299 0.0; 8880 -1.7; 9502 -4.4; 10167 -4.8; 10879 -2.6; 11640 -0.2; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -2.1
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.866541846031034dB` and instead set Global volume in the UI for both channels to **-58**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Street by 50 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.3dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 74 Hz   |  0.73 | -7.8 dB |
| Peaking | 155 Hz  |  0.95 | -6.5 dB |
| Peaking | 319 Hz  |  1.55 | -6.1 dB |
| Peaking | 2483 Hz |  1.99 | -6.6 dB |
| Peaking | 4817 Hz |  4.46 | 7.0 dB  |
| Peaking | 19 Hz   |  2.77 | 2.3 dB  |
| Peaking | 496 Hz  |  3.66 | -4.2 dB |
| Peaking | 695 Hz  |  2.26 | 4.7 dB  |
| Peaking | 6664 Hz | 10.93 | 4.5 dB  |
| Peaking | 9939 Hz |  5.06 | -5.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Street%20by%2050/Street%20by%2050.png)