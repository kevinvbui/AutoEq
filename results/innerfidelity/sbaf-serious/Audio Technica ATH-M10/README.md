# Audio Technica ATH-M10

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 5.4; 95 4.9; 102 4.0; 109 3.2; 117 2.7; 125 2.2; 134 1.8; 143 1.5; 153 1.2; 164 1.7; 175 1.0; 188 0.7; 201 0.6; 215 0.4; 230 0.2; 246 0.0; 263 -0.1; 282 -0.3; 301 -0.5; 323 -0.6; 345 -0.6; 369 -0.5; 395 -0.6; 423 -0.4; 452 -0.4; 484 -0.6; 518 -0.7; 554 -0.5; 593 -0.4; 635 -0.5; 679 -0.8; 726 -1.0; 777 -1.2; 832 -1.7; 890 -2.3; 952 -2.0; 1019 0.5; 1090 0.7; 1167 1.1; 1248 -0.7; 1336 -0.8; 1429 -0.6; 1529 0.1; 1636 1.3; 1751 2.4; 1873 3.1; 2004 3.4; 2145 4.0; 2295 5.6; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 3.3; 6775 2.5; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.1; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio Technica ATH-M10 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 55 Hz   | 0.27 | 7.3 dB  |
| Peaking | 194 Hz  | 0.49 | -3.6 dB |
| Peaking | 876 Hz  | 4.36 | -2.8 dB |
| Peaking | 1420 Hz | 4.56 | -2.8 dB |
| Peaking | 3416 Hz | 0.76 | 6.8 dB  |
| Peaking | 82 Hz   | 5.85 | 1.0 dB  |
| Peaking | 3518 Hz | 5.18 | -0.9 dB |
| Peaking | 5724 Hz | 3.11 | 3.4 dB  |
| Peaking | 7894 Hz | 1.35 | -2.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audio%20Technica%20ATH-M10/Audio%20Technica%20ATH-M10.png)