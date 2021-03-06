# Sony MDR-Z7

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.5dB
GraphicEQ: 10 -84; 20 3.0; 22 1.6; 23 0.9; 25 -0.2; 26 -0.6; 28 -1.5; 30 -2.1; 32 -2.6; 35 -3.1; 37 -3.4; 40 -3.6; 42 -3.6; 45 -3.7; 49 -3.7; 52 -3.6; 56 -3.6; 59 -3.5; 64 -3.4; 68 -3.4; 73 -3.2; 78 -3.1; 83 -2.9; 89 -2.9; 95 -3.2; 102 -3.7; 109 -4.1; 117 -4.1; 125 -3.6; 134 -4.0; 143 -4.7; 153 -5.5; 164 -5.2; 175 -4.5; 188 -4.7; 201 -4.5; 215 -4.2; 230 -3.8; 246 -3.5; 263 -3.1; 282 -2.6; 301 -2.1; 323 -1.6; 345 -1.2; 369 -0.8; 395 -0.4; 423 0.1; 452 0.3; 484 0.2; 518 0.3; 554 0.4; 593 0.6; 635 0.4; 679 0.1; 726 -0.4; 777 -0.7; 832 -1.1; 890 -1.1; 952 -0.6; 1019 0.2; 1090 1.5; 1167 3.5; 1248 4.3; 1336 4.4; 1429 4.1; 1529 3.0; 1636 1.5; 1751 -0.2; 1873 -1.5; 2004 -2.7; 2145 -3.7; 2295 -4.4; 2455 -4.7; 2627 -3.9; 2811 -2.9; 3008 -1.7; 3219 0.1; 3444 2.2; 3685 3.1; 3943 2.2; 4219 0.9; 4514 -0.3; 4830 0.4; 5168 2.4; 5530 3.4; 5917 2.8; 6331 1.4; 6775 0.5; 7249 1.2; 7756 0.3; 8299 -0.2; 8880 -1.8; 9502 -1.4; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.536193961762703dB` and instead set Global volume in the UI for both channels to **-45**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony MDR-Z7 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.1dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 18 Hz   | 1.48 | 5.5 dB  |
| Peaking | 38 Hz   | 0.53 | -4.2 dB |
| Peaking | 172 Hz  | 1.15 | -4.5 dB |
| Peaking | 1342 Hz | 3.46 | 5.4 dB  |
| Peaking | 2332 Hz | 3.66 | -5.5 dB |
| Peaking | 490 Hz  | 2.2  | 1.5 dB  |
| Peaking | 1130 Hz | 0.22 | -0.5 dB |
| Peaking | 3680 Hz | 6.51 | 4.0 dB  |
| Peaking | 5632 Hz | 4.57 | 3.8 dB  |
| Peaking | 9073 Hz | 7.51 | -2.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20MDR-Z7/Sony%20MDR-Z7.png)