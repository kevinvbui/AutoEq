# Westone UM1

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 5.9; 42 5.7; 45 5.4; 49 4.9; 52 4.6; 56 4.2; 59 3.9; 64 3.5; 68 3.1; 73 2.8; 78 2.4; 83 2.1; 89 1.7; 95 1.5; 102 1.2; 109 0.9; 117 0.7; 125 0.5; 134 0.2; 143 -0.1; 153 -0.3; 164 -0.4; 175 -0.6; 188 -0.6; 201 -0.7; 215 -0.7; 230 -0.8; 246 -0.8; 263 -0.8; 282 -0.7; 301 -0.7; 323 -0.6; 345 -0.5; 369 -0.3; 395 -0.3; 423 -0.2; 452 -0.2; 484 -0.1; 518 0.0; 554 0.4; 593 0.6; 635 0.7; 679 0.9; 726 0.9; 777 0.8; 832 0.7; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.6; 1248 -0.8; 1336 -1.2; 1429 -1.5; 1529 -1.8; 1636 -1.8; 1751 -1.7; 1873 -1.2; 2004 -0.6; 2145 0.1; 2295 1.0; 2455 2.2; 2627 3.3; 2811 4.5; 3008 5.6; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 5.8; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Westone UM1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 29 Hz   | 0.44 | 6.4 dB  |
| Peaking | 182 Hz  | 0.59 | -1.4 dB |
| Peaking | 710 Hz  | 1.9  | 1.2 dB  |
| Peaking | 1712 Hz | 1.61 | -3.7 dB |
| Peaking | 3955 Hz | 0.95 | 7.2 dB  |
| Peaking | 3038 Hz | 5.16 | 1.3 dB  |
| Peaking | 4071 Hz | 4.02 | -1.0 dB |
| Peaking | 6317 Hz | 2.28 | 4.8 dB  |
| Peaking | 7434 Hz | 0.67 | -1.3 dB |
| Peaking | 7528 Hz | 2.72 | -3.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Westone%20UM1/Westone%20UM1.png)