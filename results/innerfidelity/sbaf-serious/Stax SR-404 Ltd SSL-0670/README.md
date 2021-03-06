# Stax SR-404 Ltd SSL-0670

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.9dB
GraphicEQ: 10 -84; 20 5.8; 22 5.6; 23 5.5; 25 5.4; 26 5.3; 28 5.2; 30 5.1; 32 5.0; 35 5.0; 37 5.0; 40 5.0; 42 5.0; 45 5.0; 49 5.0; 52 5.0; 56 5.0; 59 4.9; 64 4.7; 68 4.3; 73 4.0; 78 3.8; 83 3.7; 89 3.5; 95 3.4; 102 3.1; 109 2.8; 117 2.7; 125 2.5; 134 2.4; 143 2.3; 153 2.2; 164 2.1; 175 2.0; 188 1.9; 201 1.8; 215 1.8; 230 1.8; 246 1.8; 263 1.8; 282 1.8; 301 1.9; 323 2.0; 345 2.0; 369 1.9; 395 1.9; 423 2.0; 452 2.0; 484 1.8; 518 1.6; 554 1.7; 593 1.7; 635 1.6; 679 1.4; 726 1.2; 777 1.3; 832 0.9; 890 0.6; 952 0.4; 1019 -0.0; 1090 -0.3; 1167 -0.8; 1248 -1.3; 1336 -1.9; 1429 -2.6; 1529 -3.1; 1636 -3.4; 1751 -3.3; 1873 -1.8; 2004 -0.1; 2145 1.5; 2295 2.1; 2455 2.0; 2627 1.6; 2811 0.7; 3008 1.0; 3219 1.1; 3444 0.9; 3685 1.3; 3943 3.0; 4219 3.2; 4514 2.0; 4830 1.8; 5168 2.6; 5530 2.3; 5917 0.3; 6331 2.1; 6775 3.7; 7249 1.3; 7756 0.3; 8299 -0.6; 8880 -3.1; 9502 -3.6; 10167 -2.4; 10879 -0.5; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -0.8; 18692 -2.9; 20000 -4.3
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.883322192620013dB` and instead set Global volume in the UI for both channels to **-58**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Stax SR-404 Ltd SSL-0670 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.6dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 30 Hz   | 0.42 | 3.9 dB  |
| Peaking | 162 Hz  | 0.03 | 1.6 dB  |
| Peaking | 1539 Hz | 2.21 | -5.3 dB |
| Peaking | 5986 Hz | 0.79 | 1.9 dB  |
| Peaking | 9338 Hz | 3.52 | -5.3 dB |
| Peaking | 1013 Hz | 5    | -0.4 dB |
| Peaking | 2287 Hz | 5.03 | 2.4 dB  |
| Peaking | 2708 Hz | 1.08 | -0.7 dB |
| Peaking | 3744 Hz | 3.74 | -0.9 dB |
| Peaking | 4035 Hz | 7.88 | 2.3 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Stax%20SR-404%20Ltd%20SSL-0670/Stax%20SR-404%20Ltd%20SSL-0670.png)