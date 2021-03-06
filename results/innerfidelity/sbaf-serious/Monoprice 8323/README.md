# Monoprice 8323

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 5.9; 49 5.1; 52 4.4; 56 3.7; 59 3.3; 64 2.8; 68 2.5; 73 2.3; 78 2.2; 83 2.1; 89 2.0; 95 2.0; 102 2.0; 109 2.1; 117 2.2; 125 2.1; 134 1.9; 143 1.8; 153 1.6; 164 2.0; 175 2.1; 188 1.8; 201 1.8; 215 1.8; 230 1.9; 246 1.9; 263 2.1; 282 2.5; 301 3.0; 323 3.2; 345 3.3; 369 3.2; 395 2.9; 423 2.5; 452 2.1; 484 1.6; 518 1.3; 554 1.2; 593 1.2; 635 1.0; 679 0.7; 726 0.5; 777 0.5; 832 0.3; 890 0.1; 952 -0.0; 1019 0.0; 1090 0.5; 1167 0.2; 1248 -0.2; 1336 -0.4; 1429 -0.5; 1529 -1.0; 1636 -1.1; 1751 -0.7; 1873 0.4; 2004 1.4; 2145 2.3; 2295 3.7; 2455 5.3; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.9; 8880 -2.1; 9502 -1.7; 10167 -0.1; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Monoprice 8323 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 30 Hz   | 0.65 | 6.5 dB  |
| Peaking | 162 Hz  | 1.18 | 1.1 dB  |
| Peaking | 351 Hz  | 1.9  | 3.1 dB  |
| Peaking | 4385 Hz | 0.86 | 7.1 dB  |
| Peaking | 8837 Hz | 3.01 | -4.4 dB |
| Peaking | 1673 Hz | 2.19 | -3.1 dB |
| Peaking | 2182 Hz | 4.34 | -1.0 dB |
| Peaking | 2562 Hz | 1.98 | 4.0 dB  |
| Peaking | 4411 Hz | 0.87 | -1.6 dB |
| Peaking | 6084 Hz | 4.08 | 2.5 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Monoprice%208323/Monoprice%208323.png)