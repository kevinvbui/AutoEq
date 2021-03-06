# Sennheiser HD 438

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.9; 40 5.6; 42 5.3; 45 4.9; 49 4.6; 52 4.6; 56 4.7; 59 4.6; 64 4.0; 68 3.3; 73 3.2; 78 4.4; 83 5.9; 89 5.7; 95 4.3; 102 3.6; 109 3.2; 117 2.9; 125 2.6; 134 2.5; 143 2.4; 153 2.6; 164 2.9; 175 2.6; 188 3.6; 201 4.0; 215 3.7; 230 4.5; 246 4.7; 263 4.3; 282 4.4; 301 4.8; 323 4.9; 345 4.1; 369 3.9; 395 3.6; 423 3.4; 452 3.4; 484 3.0; 518 2.6; 554 2.3; 593 2.1; 635 2.2; 679 2.2; 726 2.2; 777 1.8; 832 1.3; 890 0.5; 952 0.0; 1019 0.2; 1090 0.4; 1167 1.2; 1248 0.7; 1336 -0.4; 1429 0.1; 1529 1.0; 1636 1.7; 1751 2.5; 1873 3.3; 2004 4.3; 2145 4.9; 2295 5.8; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1066924050392615dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 438 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 27 Hz   | 0.45 | 6.1 dB  |
| Peaking | 88 Hz   | 4.6  | 3.2 dB  |
| Peaking | 270 Hz  | 1.09 | 4.2 dB  |
| Peaking | 474 Hz  | 1.84 | 1.3 dB  |
| Peaking | 3663 Hz | 0.83 | 6.9 dB  |
| Peaking | 1393 Hz | 3.11 | -2.0 dB |
| Peaking | 2294 Hz | 2.53 | 2.0 dB  |
| Peaking | 3583 Hz | 2.36 | -1.3 dB |
| Peaking | 6254 Hz | 2.36 | 5.3 dB  |
| Peaking | 7418 Hz | 1.51 | -4.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20438/Sennheiser%20HD%20438.png)