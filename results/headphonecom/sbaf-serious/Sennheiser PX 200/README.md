# Sennheiser PX 200

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 6.0; 188 6.0; 201 6.0; 215 6.0; 230 6.0; 246 6.0; 263 6.0; 282 6.0; 301 6.0; 323 5.9; 345 5.6; 369 5.5; 395 5.0; 423 4.8; 452 4.5; 484 3.8; 518 3.3; 554 2.8; 593 2.3; 635 1.5; 679 0.9; 726 0.6; 777 0.0; 832 -0.1; 890 -0.1; 952 -0.1; 1019 0.0; 1090 0.1; 1167 0.3; 1248 0.2; 1336 0.1; 1429 -0.3; 1529 -0.7; 1636 -1.0; 1751 -1.1; 1873 -1.2; 2004 -1.0; 2145 -0.4; 2295 0.7; 2455 1.2; 2627 1.7; 2811 2.5; 3008 3.7; 3219 4.7; 3444 5.4; 3685 5.9; 3943 6.0; 4219 5.3; 4514 3.6; 4830 4.3; 5168 5.7; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000003dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser PX 200 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 34 Hz   | 0.09 | 6.0 dB  |
| Peaking | 354 Hz  | 0.82 | 3.6 dB  |
| Peaking | 1828 Hz | 0.19 | -2.0 dB |
| Peaking | 3612 Hz | 1.73 | 7.1 dB  |
| Peaking | 5867 Hz | 2.75 | 6.4 dB  |
| Peaking | 797 Hz  | 3.95 | -0.8 dB |
| Peaking | 1242 Hz | 2.58 | 1.1 dB  |
| Peaking | 1989 Hz | 2.54 | -1.4 dB |
| Peaking | 2326 Hz | 3.54 | 1.1 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20PX%20200/Sennheiser%20PX%20200.png)