# California Headphone Lorado

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 5.9; 37 5.6; 40 4.8; 42 4.2; 45 3.3; 49 2.4; 52 1.9; 56 1.2; 59 0.6; 64 -0.1; 68 -0.4; 73 -0.5; 78 -0.8; 83 -1.5; 89 -2.5; 95 -2.8; 102 -2.5; 109 -2.3; 117 -2.5; 125 -2.9; 134 -3.1; 143 -3.2; 153 -3.4; 164 -2.6; 175 -2.8; 188 -3.3; 201 -3.8; 215 -3.5; 230 -3.1; 246 -2.8; 263 -2.5; 282 -1.9; 301 -1.3; 323 -0.7; 345 -0.4; 369 -0.2; 395 -0.0; 423 0.2; 452 0.2; 484 0.2; 518 0.3; 554 0.6; 593 0.8; 635 0.9; 679 0.8; 726 0.8; 777 1.0; 832 0.8; 890 0.5; 952 0.3; 1019 -0.0; 1090 -0.3; 1167 -0.5; 1248 -0.8; 1336 -1.7; 1429 -1.7; 1529 -2.1; 1636 -3.0; 1751 -3.1; 1873 -2.9; 2004 -2.2; 2145 -0.8; 2295 0.3; 2455 1.8; 2627 3.3; 2811 4.5; 3008 5.9; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 3.9; 5530 5.8; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.9; 10167 -1.9; 10879 -0.8; 11640 0.0; 12455 0.0; 13327 -0.6; 14260 -1.7; 15258 -0.1; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `California Headphone Lorado ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 28 Hz    | 0.9  | 6.9 dB  |
| Peaking | 136 Hz   | 0.74 | -3.8 dB |
| Peaking | 1815 Hz  | 2.32 | -5.0 dB |
| Peaking | 3501 Hz  | 1.31 | 6.9 dB  |
| Peaking | 5984 Hz  | 4.3  | 4.5 dB  |
| Peaking | 229 Hz   | 3.73 | -1.4 dB |
| Peaking | 576 Hz   | 1.16 | 1.2 dB  |
| Peaking | 4666 Hz  | 8.27 | 1.6 dB  |
| Peaking | 11361 Hz | 1.64 | -3.5 dB |
| Peaking | 11679 Hz | 3.7  | 3.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/California%20Headphone%20Lorado/California%20Headphone%20Lorado.png)