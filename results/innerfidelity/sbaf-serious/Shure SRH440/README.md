# Shure SRH440

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 5.8; 40 5.1; 42 4.5; 45 3.7; 49 2.8; 52 2.2; 56 1.5; 59 0.9; 64 0.1; 68 -0.4; 73 -0.7; 78 -0.9; 83 -0.7; 89 -0.3; 95 0.3; 102 -0.3; 109 -1.6; 117 -2.5; 125 -2.9; 134 -2.6; 143 -2.3; 153 -2.0; 164 -0.8; 175 -0.9; 188 -1.5; 201 -1.4; 215 -1.0; 230 -0.9; 246 -0.8; 263 -0.9; 282 -0.8; 301 -0.8; 323 -0.8; 345 -1.2; 369 -2.0; 395 -2.0; 423 -1.5; 452 -1.4; 484 -1.3; 518 -1.2; 554 -0.9; 593 -0.6; 635 -0.5; 679 -0.5; 726 -0.5; 777 -0.3; 832 -0.3; 890 -0.3; 952 -0.2; 1019 0.1; 1090 0.8; 1167 0.6; 1248 0.3; 1336 -0.1; 1429 -0.7; 1529 -1.2; 1636 -1.4; 1751 -1.5; 1873 -1.3; 2004 -1.1; 2145 -0.5; 2295 -0.1; 2455 0.5; 2627 0.4; 2811 0.2; 3008 0.4; 3219 -0.7; 3444 -0.8; 3685 -1.0; 3943 0.3; 4219 0.7; 4514 1.0; 4830 2.3; 5168 3.1; 5530 2.9; 5917 5.2; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.7; 8299 -3.5; 8880 -5.3; 9502 -6.1; 10167 -5.4; 10879 -2.7; 11640 -0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SRH440 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 28 Hz    | 1.04 | 6.9 dB  |
| Peaking | 128 Hz   | 1.59 | -2.7 dB |
| Peaking | 412 Hz   | 1.62 | -1.6 dB |
| Peaking | 6232 Hz  | 3.03 | 6.6 dB  |
| Peaking | 9296 Hz  | 2.99 | -7.3 dB |
| Peaking | 70 Hz    | 2.72 | -3.3 dB |
| Peaking | 73 Hz    | 1.41 | 1.8 dB  |
| Peaking | 1751 Hz  | 4.17 | -1.7 dB |
| Peaking | 10545 Hz | 6.04 | -2.4 dB |
| Peaking | 11378 Hz | 3.03 | 1.9 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Shure%20SRH440/Shure%20SRH440.png)