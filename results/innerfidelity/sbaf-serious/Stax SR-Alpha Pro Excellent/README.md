# Stax SR-Alpha Pro Excellent

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 5.8; 52 4.9; 56 3.5; 59 2.7; 64 1.6; 68 0.4; 73 -1.5; 78 -2.9; 83 -3.3; 89 -3.2; 95 -3.1; 102 -3.2; 109 -2.6; 117 -2.1; 125 -1.6; 134 -1.2; 143 -0.9; 153 -0.7; 164 -0.5; 175 -0.3; 188 -0.1; 201 -0.0; 215 0.2; 230 0.3; 246 0.4; 263 0.5; 282 0.6; 301 0.6; 323 0.7; 345 0.7; 369 0.8; 395 0.8; 423 1.0; 452 1.1; 484 1.0; 518 1.0; 554 1.1; 593 1.1; 635 1.1; 679 0.9; 726 0.8; 777 0.9; 832 0.7; 890 0.5; 952 0.3; 1019 -0.0; 1090 -0.2; 1167 -0.6; 1248 -1.0; 1336 -1.6; 1429 -2.1; 1529 -2.6; 1636 -3.0; 1751 -3.2; 1873 -2.9; 2004 -2.1; 2145 -1.3; 2295 -1.2; 2455 -0.8; 2627 -0.1; 2811 0.5; 3008 1.4; 3219 1.8; 3444 2.5; 3685 2.7; 3943 3.5; 4219 3.1; 4514 3.2; 4830 4.0; 5168 4.8; 5530 4.8; 5917 3.2; 6331 1.4; 6775 0.5; 7249 0.1; 7756 -1.2; 8299 -3.3; 8880 -4.8; 9502 -4.5; 10167 -2.6; 10879 -0.4; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 -0.2
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-Alpha Pro Excellent ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.5dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 61 Hz    | 0.29 | 19.6 dB  |
| Peaking | 86 Hz    | 0.54 | -21.6 dB |
| Peaking | 1739 Hz  | 2.03 | -3.9 dB  |
| Peaking | 4923 Hz  | 1.26 | 4.7 dB   |
| Peaking | 8941 Hz  | 3.07 | -6.2 dB  |
| Peaking | 670 Hz   | 2.19 | 0.6 dB   |
| Peaking | 4608 Hz  | 8.05 | -1.4 dB  |
| Peaking | 5544 Hz  | 3.21 | 1.4 dB   |
| Peaking | 6336 Hz  | 5.5  | -1.7 dB  |
| Peaking | 11295 Hz | 7.26 | 0.9 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-Alpha%20Pro%20Excellent/Stax%20SR-Alpha%20Pro%20Excellent.png)