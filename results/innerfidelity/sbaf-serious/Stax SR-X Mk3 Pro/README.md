# Stax SR-X Mk3 Pro

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 5.9; 28 5.7; 30 5.4; 32 5.1; 35 4.6; 37 4.4; 40 4.1; 42 4.0; 45 3.8; 49 3.7; 52 3.6; 56 3.5; 59 3.4; 64 3.3; 68 3.2; 73 3.0; 78 2.8; 83 2.6; 89 2.3; 95 2.1; 102 1.9; 109 1.8; 117 1.7; 125 1.6; 134 1.4; 143 1.2; 153 1.1; 164 1.1; 175 1.0; 188 1.0; 201 0.9; 215 0.9; 230 0.9; 246 0.9; 263 0.9; 282 0.9; 301 0.9; 323 0.9; 345 0.9; 369 1.0; 395 1.0; 423 1.0; 452 1.0; 484 0.8; 518 0.3; 554 0.9; 593 1.2; 635 1.0; 679 0.7; 726 0.6; 777 0.7; 832 0.5; 890 0.3; 952 0.0; 1019 0.1; 1090 0.1; 1167 0.2; 1248 0.0; 1336 0.4; 1429 0.7; 1529 0.8; 1636 1.1; 1751 1.6; 1873 2.1; 2004 2.0; 2145 1.8; 2295 1.3; 2455 0.5; 2627 -0.3; 2811 -1.1; 3008 -2.0; 3219 -2.3; 3444 -2.5; 3685 -3.3; 3943 -3.8; 4219 -3.8; 4514 -2.4; 4830 -0.4; 5168 0.9; 5530 0.9; 5917 0.1; 6331 -1.1; 6775 -1.9; 7249 -2.3; 7756 -2.3; 8299 -2.7; 8880 -2.6; 9502 -0.9; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.0; 18692 -2.8; 20000 -6.4
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-X Mk3 Pro ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.2dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 13 Hz   | 0.27 | 5.7 dB  |
| Peaking | 84 Hz   | 0.09 | 0.8 dB  |
| Peaking | 1977 Hz | 3.29 | 2.4 dB  |
| Peaking | 3778 Hz | 2.93 | -4.0 dB |
| Peaking | 8126 Hz | 3.48 | -2.9 dB |
| Peaking | 2373 Hz | 5.79 | 0.2 dB  |
| Peaking | 2975 Hz | 5.6  | -1.4 dB |
| Peaking | 4375 Hz | 5.2  | -3.3 dB |
| Peaking | 5055 Hz | 1.64 | 2.9 dB  |
| Peaking | 6652 Hz | 3.68 | -2.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-X%20Mk3%20Pro/Stax%20SR-X%20Mk3%20Pro.png)