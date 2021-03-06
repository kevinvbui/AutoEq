# AKG K612

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.9dB
GraphicEQ: 10 -84; 20 5.8; 22 5.2; 23 4.9; 25 4.4; 26 4.1; 28 3.7; 30 3.4; 32 3.0; 35 2.6; 37 2.3; 40 2.0; 42 1.8; 45 1.5; 49 1.2; 52 1.0; 56 0.7; 59 0.5; 64 0.2; 68 0.0; 73 0.4; 78 0.8; 83 0.1; 89 -0.6; 95 -0.2; 102 -0.6; 109 -1.1; 117 -1.5; 125 -1.9; 134 -2.1; 143 -2.3; 153 -2.5; 164 -2.5; 175 -2.5; 188 -2.6; 201 -2.7; 215 -2.6; 230 -2.5; 246 -2.5; 263 -2.5; 282 -2.4; 301 -2.3; 323 -2.0; 345 -1.9; 369 -1.7; 395 -1.7; 423 -1.5; 452 -1.4; 484 -1.3; 518 -1.3; 554 -0.9; 593 -0.2; 635 0.3; 679 0.0; 726 0.3; 777 0.5; 832 0.2; 890 0.0; 952 -0.0; 1019 0.0; 1090 0.0; 1167 0.3; 1248 0.5; 1336 0.2; 1429 -0.3; 1529 -0.9; 1636 -1.2; 1751 -1.8; 1873 -2.5; 2004 -3.5; 2145 -4.0; 2295 -4.2; 2455 -4.3; 2627 -4.2; 2811 -3.4; 3008 -2.4; 3219 -1.4; 3444 0.3; 3685 0.9; 3943 -0.0; 4219 -1.7; 4514 -2.5; 4830 -1.4; 5168 0.5; 5530 1.2; 5917 -0.0; 6331 -1.0; 6775 -1.4; 7249 -2.2; 7756 -2.6; 8299 -3.4; 8880 -3.5; 9502 -1.2; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 -0.2; 17469 -2.5; 18692 -3.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.863799457642276dB` and instead set Global volume in the UI for both channels to **-58**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AKG K612 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 15 Hz    | 0.62 | 6.5 dB  |
| Peaking | 204 Hz   | 0.79 | -2.9 dB |
| Peaking | 2366 Hz  | 2.53 | -4.8 dB |
| Peaking | 8305 Hz  | 3.85 | -3.7 dB |
| Peaking | 18285 Hz | 3.28 | -3.7 dB |
| Peaking | 1064 Hz  | 1.36 | 0.8 dB  |
| Peaking | 3709 Hz  | 4.04 | 4.5 dB  |
| Peaking | 4471 Hz  | 1.52 | -4.3 dB |
| Peaking | 5418 Hz  | 4.38 | 4.5 dB  |
| Peaking | 10770 Hz | 1.6  | 0.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/AKG%20K612/AKG%20K612.png)