# Superlux HD 668B

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 5.9; 30 5.6; 32 5.0; 35 3.9; 37 3.1; 40 2.0; 42 1.3; 45 0.4; 49 -0.8; 52 -1.6; 56 -2.5; 59 -3.1; 64 -3.7; 68 -4.0; 73 -3.9; 78 -4.0; 83 -4.4; 89 -4.9; 95 -5.6; 102 -5.7; 109 -5.3; 117 -4.8; 125 -4.9; 134 -5.0; 143 -4.9; 153 -4.5; 164 -4.0; 175 -3.9; 188 -3.6; 201 -3.4; 215 -3.1; 230 -2.6; 246 -2.8; 263 -2.9; 282 -2.6; 301 -2.5; 323 -2.3; 345 -1.9; 369 -1.6; 395 -1.4; 423 -1.1; 452 -0.8; 484 -0.8; 518 -0.8; 554 -0.7; 593 -0.1; 635 0.4; 679 0.2; 726 0.1; 777 0.2; 832 0.1; 890 0.1; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.3; 1248 -0.5; 1336 -1.1; 1429 -1.9; 1529 -3.0; 1636 -4.0; 1751 -5.0; 1873 -5.9; 2004 -6.3; 2145 -6.5; 2295 -6.2; 2455 -6.0; 2627 -5.4; 2811 -4.5; 3008 -3.9; 3219 -3.2; 3444 -2.3; 3685 -1.5; 3943 -1.2; 4219 -1.4; 4514 -0.9; 4830 -0.4; 5168 -1.4; 5530 -10.5; 5917 -8.8; 6331 -5.9; 6775 -5.1; 7249 -6.1; 7756 -8.5; 8299 -10.9; 8880 -12.0; 9502 -10.8; 10167 -8.1; 10879 -5.3; 11640 -3.3; 12455 -2.3; 13327 -2.8; 14260 -4.7; 15258 -6.2; 16326 -5.7; 17469 -3.5; 18692 -1.7; 20000 -1.3
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1000000000000005dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Superlux HD 668B ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 27 Hz    | 0.84 | 8.3 dB   |
| Peaking | 91 Hz    | 0.49 | -6.3 dB  |
| Peaking | 2170 Hz  | 1.94 | -6.7 dB  |
| Peaking | 8609 Hz  | 1.56 | -11.2 dB |
| Peaking | 15996 Hz | 2.52 | -5.8 dB  |
| Peaking | 838 Hz   | 1.77 | 1.1 dB   |
| Peaking | 5088 Hz  | 4.73 | 6.4 dB   |
| Peaking | 5583 Hz  | 6.44 | -11.1 dB |
| Peaking | 7018 Hz  | 5.65 | 2.5 dB   |
| Peaking | 12129 Hz | 6.09 | 2.1 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Superlux%20HD%20668B/Superlux%20HD%20668B.png)