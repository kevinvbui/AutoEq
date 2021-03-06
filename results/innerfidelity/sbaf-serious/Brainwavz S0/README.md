# Brainwavz S0

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.3dB
GraphicEQ: 10 -84; 20 -6.7; 22 -6.9; 23 -7.0; 25 -7.1; 26 -7.2; 28 -7.3; 30 -7.4; 32 -7.5; 35 -7.6; 37 -7.7; 40 -7.9; 42 -7.9; 45 -8.0; 49 -8.2; 52 -8.3; 56 -8.5; 59 -8.6; 64 -8.8; 68 -9.0; 73 -9.1; 78 -9.4; 83 -9.5; 89 -9.7; 95 -9.9; 102 -10.0; 109 -9.9; 117 -10.0; 125 -10.1; 134 -10.1; 143 -10.1; 153 -10.0; 164 -10.0; 175 -9.7; 188 -9.6; 201 -9.4; 215 -9.1; 230 -8.8; 246 -8.5; 263 -8.2; 282 -7.9; 301 -7.4; 323 -7.0; 345 -6.6; 369 -6.1; 395 -5.7; 423 -5.1; 452 -4.6; 484 -4.3; 518 -3.8; 554 -3.2; 593 -2.5; 635 -2.1; 679 -1.9; 726 -1.4; 777 -0.9; 832 -0.5; 890 -0.5; 952 -0.2; 1019 0.1; 1090 0.3; 1167 0.2; 1248 0.5; 1336 0.7; 1429 1.1; 1529 0.6; 1636 -1.0; 1751 -2.4; 1873 -2.7; 2004 -2.4; 2145 -2.0; 2295 -1.6; 2455 -0.9; 2627 -0.4; 2811 0.2; 3008 1.0; 3219 1.3; 3444 1.5; 3685 0.8; 3943 -0.1; 4219 -2.5; 4514 -4.9; 4830 -7.0; 5168 -8.5; 5530 -6.6; 5917 -2.0; 6331 1.4; 6775 3.2; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-3.3362884368748937dB` and instead set Global volume in the UI for both channels to **-33**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Brainwavz S0 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -0.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 31 Hz   | 0.3  | -6.7 dB |
| Peaking | 118 Hz  | 0.7  | -5.5 dB |
| Peaking | 230 Hz  | 1.01 | -4.5 dB |
| Peaking | 400 Hz  | 1.57 | -2.4 dB |
| Peaking | 5085 Hz | 5.81 | -9.5 dB |
| Peaking | 1508 Hz | 1.89 | 4.1 dB  |
| Peaking | 1809 Hz | 2.06 | -5.2 dB |
| Peaking | 3500 Hz | 2.42 | 4.0 dB  |
| Peaking | 4301 Hz | 1.5  | -2.5 dB |
| Peaking | 6707 Hz | 6.02 | 4.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Brainwavz%20S0/Brainwavz%20S0.png)