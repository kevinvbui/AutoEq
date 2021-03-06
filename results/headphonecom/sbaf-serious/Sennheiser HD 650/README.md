# Sennheiser HD 650

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.7dB
GraphicEQ: 10 -84; 20 5.6; 22 4.9; 23 4.5; 25 3.9; 26 3.6; 28 3.1; 30 2.6; 32 2.2; 35 1.7; 37 1.4; 40 1.4; 42 1.5; 45 1.8; 49 1.3; 52 0.6; 56 -0.1; 59 -0.4; 64 -0.5; 68 -0.5; 73 -0.8; 78 -1.3; 83 -1.6; 89 -2.0; 95 -2.3; 102 -2.4; 109 -2.5; 117 -2.7; 125 -2.8; 134 -3.0; 143 -3.2; 153 -3.2; 164 -3.1; 175 -3.1; 188 -3.0; 201 -3.0; 215 -2.8; 230 -2.6; 246 -2.4; 263 -2.3; 282 -2.3; 301 -2.0; 323 -1.8; 345 -1.7; 369 -1.4; 395 -1.2; 423 -1.2; 452 -0.9; 484 -0.8; 518 -0.7; 554 -0.4; 593 -0.1; 635 0.0; 679 0.0; 726 0.1; 777 0.4; 832 0.1; 890 -0.1; 952 0.1; 1019 -0.0; 1090 -0.2; 1167 -0.4; 1248 -0.5; 1336 -0.5; 1429 -0.6; 1529 -0.8; 1636 -1.0; 1751 -1.1; 1873 -1.3; 2004 -1.4; 2145 -1.4; 2295 -1.2; 2455 -1.0; 2627 -1.0; 2811 -0.9; 3008 -0.6; 3219 -0.3; 3444 0.5; 3685 1.4; 3943 1.9; 4219 1.1; 4514 -0.0; 4830 0.5; 5168 2.5; 5530 3.3; 5917 2.4; 6331 1.6; 6775 2.1; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.9; 9502 -1.3; 10167 -0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.687303770231208dB` and instead set Global volume in the UI for both channels to **-56**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 650 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.3dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 12 Hz   |  0.57 | 7.5 dB  |
| Peaking | 154 Hz  |  0.65 | -3.4 dB |
| Peaking | 2218 Hz |  1.55 | -1.5 dB |
| Peaking | 3799 Hz |  6.38 | 2.0 dB  |
| Peaking | 5723 Hz |  3.89 | 3.3 dB  |
| Peaking | 750 Hz  |  2.86 | 0.7 dB  |
| Peaking | 6950 Hz | 11.13 | 1.4 dB  |
| Peaking | 9218 Hz |  7.61 | -1.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20650/Sennheiser%20HD%20650.png)