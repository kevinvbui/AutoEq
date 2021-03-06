# Comradz NW-STUDIO PRO

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 5.9; 23 5.7; 25 5.3; 26 5.0; 28 4.4; 30 3.8; 32 3.3; 35 2.6; 37 2.2; 40 1.6; 42 1.3; 45 0.8; 49 0.2; 52 -0.1; 56 -0.5; 59 -0.8; 64 -1.2; 68 -1.5; 73 -1.8; 78 -2.1; 83 -2.3; 89 -2.6; 95 -2.8; 102 -3.0; 109 -3.0; 117 -3.1; 125 -3.3; 134 -3.5; 143 -3.6; 153 -3.7; 164 -3.9; 175 -3.9; 188 -4.0; 201 -4.1; 215 -4.2; 230 -4.1; 246 -4.2; 263 -4.3; 282 -4.0; 301 -3.9; 323 -3.8; 345 -3.6; 369 -3.2; 395 -3.0; 423 -2.6; 452 -2.3; 484 -2.1; 518 -1.7; 554 -1.1; 593 -0.4; 635 0.1; 679 0.6; 726 1.4; 777 2.1; 832 2.6; 890 2.4; 952 1.4; 1019 -0.7; 1090 -3.3; 1167 -6.3; 1248 -9.5; 1336 -12.5; 1429 -15.0; 1529 -16.4; 1636 -16.4; 1751 -15.6; 1873 -14.4; 2004 -12.8; 2145 -11.2; 2295 -9.5; 2455 -7.5; 2627 -6.0; 2811 -4.4; 3008 -2.3; 3219 -1.0; 3444 -0.1; 3685 -0.3; 3943 -1.3; 4219 -3.7; 4514 -5.6; 4830 -6.6; 5168 -6.5; 5530 -5.6; 5917 -4.0; 6331 -2.1; 6775 0.2; 7249 -3.1; 7756 -5.2; 8299 -5.1; 8880 -2.2; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Comradz NW-STUDIO PRO ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.9dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 23 Hz    | 1.35 | 6.2 dB   |
| Peaking | 173 Hz   | 0.68 | -4.4 dB  |
| Peaking | 1682 Hz  | 2.25 | -18.1 dB |
| Peaking | 5180 Hz  | 2.99 | -6.1 dB  |
| Peaking | 22674 Hz | 2.42 | -2.0 dB  |
| Peaking | 871 Hz   | 2.66 | 6.1 dB   |
| Peaking | 1343 Hz  | 5.39 | -5.1 dB  |
| Peaking | 2270 Hz  | 4.61 | -3.2 dB  |
| Peaking | 3459 Hz  | 4.85 | 3.3 dB   |
| Peaking | 8054 Hz  | 7.46 | -5.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Comradz%20NW-STUDIO%20PRO/Comradz%20NW-STUDIO%20PRO.png)