# Klipsch X12i

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -0.8; 22 -0.9; 23 -1.0; 25 -1.1; 26 -1.2; 28 -1.3; 30 -1.4; 32 -1.5; 35 -1.6; 37 -1.7; 40 -1.8; 42 -1.9; 45 -2.0; 49 -2.2; 52 -2.3; 56 -2.5; 59 -2.6; 64 -2.9; 68 -3.1; 73 -3.3; 78 -3.5; 83 -3.8; 89 -4.1; 95 -4.3; 102 -4.5; 109 -4.6; 117 -4.7; 125 -4.9; 134 -5.1; 143 -5.1; 153 -5.2; 164 -5.3; 175 -5.2; 188 -5.2; 201 -5.2; 215 -5.1; 230 -4.9; 246 -4.8; 263 -4.7; 282 -4.5; 301 -4.3; 323 -4.0; 345 -3.8; 369 -3.6; 395 -3.3; 423 -2.9; 452 -2.6; 484 -2.4; 518 -2.1; 554 -1.7; 593 -1.1; 635 -0.8; 679 -0.7; 726 -0.4; 777 0.0; 832 0.2; 890 0.2; 952 0.1; 1019 -0.0; 1090 -0.1; 1167 -0.2; 1248 -0.2; 1336 -0.4; 1429 -0.7; 1529 -0.8; 1636 -0.8; 1751 -0.6; 1873 -0.2; 2004 0.1; 2145 0.4; 2295 0.6; 2455 0.9; 2627 1.0; 2811 0.7; 3008 0.8; 3219 1.5; 3444 3.2; 3685 5.1; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999017734476dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Klipsch X12i ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 128 Hz  | 0.49 | -4.5 dB |
| Peaking | 285 Hz  | 1    | -2.1 dB |
| Peaking | 3082 Hz | 4.79 | -1.3 dB |
| Peaking | 4157 Hz | 2.2  | 6.0 dB  |
| Peaking | 5877 Hz | 3.46 | 4.9 dB  |
| Peaking | 24 Hz   | 1.4  | -0.4 dB |
| Peaking | 837 Hz  | 3.25 | 0.9 dB  |
| Peaking | 1598 Hz | 4.02 | -1.1 dB |
| Peaking | 8257 Hz | 4.42 | -1.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Klipsch%20X12i/Klipsch%20X12i.png)