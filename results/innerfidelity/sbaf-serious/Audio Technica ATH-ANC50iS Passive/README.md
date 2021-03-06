# Audio Technica ATH-ANC50iS Passive

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -0.5; 22 -1.3; 23 -1.7; 25 -2.4; 26 -2.7; 28 -3.2; 30 -3.7; 32 -4.1; 35 -4.6; 37 -4.8; 40 -5.1; 42 -5.3; 45 -5.5; 49 -5.8; 52 -5.9; 56 -6.0; 59 -6.1; 64 -6.2; 68 -6.2; 73 -6.2; 78 -6.2; 83 -6.5; 89 -6.9; 95 -7.3; 102 -7.6; 109 -7.6; 117 -7.6; 125 -7.9; 134 -8.1; 143 -8.2; 153 -8.3; 164 -8.4; 175 -8.5; 188 -8.8; 201 -8.9; 215 -8.9; 230 -8.9; 246 -8.9; 263 -8.8; 282 -8.4; 301 -7.7; 323 -7.2; 345 -7.0; 369 -7.1; 395 -7.0; 423 -6.9; 452 -7.0; 484 -6.6; 518 -5.6; 554 -3.9; 593 -2.2; 635 -0.6; 679 0.6; 726 1.1; 777 1.8; 832 1.7; 890 0.1; 952 -0.3; 1019 0.4; 1090 1.8; 1167 2.8; 1248 4.0; 1336 4.9; 1429 5.7; 1529 6.0; 1636 6.0; 1751 6.0; 1873 6.0; 2004 6.0; 2145 6.0; 2295 6.0; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio Technica ATH-ANC50iS Passive ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 85 Hz   | 0.36 | -6.1 dB |
| Peaking | 248 Hz  | 0.89 | -5.7 dB |
| Peaking | 462 Hz  | 3.11 | -4.3 dB |
| Peaking | 2078 Hz | 0.66 | 6.4 dB  |
| Peaking | 5160 Hz | 1.92 | 4.5 dB  |
| Peaking | 791 Hz  | 3.39 | 3.5 dB  |
| Peaking | 930 Hz  | 2.8  | -3.5 dB |
| Peaking | 1394 Hz | 4.07 | 1.4 dB  |
| Peaking | 6398 Hz | 4.99 | 3.0 dB  |
| Peaking | 7780 Hz | 1.83 | -2.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audio%20Technica%20ATH-ANC50iS%20Passive/Audio%20Technica%20ATH-ANC50iS%20Passive.png)