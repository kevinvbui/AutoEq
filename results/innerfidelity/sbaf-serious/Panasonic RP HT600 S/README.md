# Panasonic RP HT600 S

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 2.7; 22 1.5; 23 0.9; 25 -0.1; 26 -0.6; 28 -1.4; 30 -2.0; 32 -2.6; 35 -3.2; 37 -3.5; 40 -3.8; 42 -3.9; 45 -4.1; 49 -4.1; 52 -4.2; 56 -4.2; 59 -4.1; 64 -4.1; 68 -4.1; 73 -4.1; 78 -4.2; 83 -4.2; 89 -4.2; 95 -4.4; 102 -4.4; 109 -4.2; 117 -4.0; 125 -4.2; 134 -4.5; 143 -4.7; 153 -4.9; 164 -4.9; 175 -4.6; 188 -4.8; 201 -5.0; 215 -5.0; 230 -5.0; 246 -5.1; 263 -5.2; 282 -5.2; 301 -5.3; 323 -5.2; 345 -5.3; 369 -5.4; 395 -5.3; 423 -5.1; 452 -5.2; 484 -5.3; 518 -5.5; 554 -5.3; 593 -4.9; 635 -4.6; 679 -4.4; 726 -4.0; 777 -3.5; 832 -2.7; 890 -1.5; 952 -0.4; 1019 0.1; 1090 0.1; 1167 -0.1; 1248 -1.2; 1336 -3.0; 1429 -4.6; 1529 -6.0; 1636 -6.5; 1751 -6.2; 1873 -5.6; 2004 -3.8; 2145 -2.4; 2295 -1.4; 2455 -0.1; 2627 1.2; 2811 2.4; 3008 3.3; 3219 3.7; 3444 4.0; 3685 3.9; 3943 5.8; 4219 6.0; 4514 3.8; 4830 3.7; 5168 5.9; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -2.1; 8880 -6.1; 9502 -6.2; 10167 -1.8; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099998284527815dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Panasonic RP HT600 S ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.4dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 189 Hz  | 0.23 | -5.2 dB |
| Peaking | 1747 Hz | 3.12 | -6.9 dB |
| Peaking | 3797 Hz | 1.29 | 4.9 dB  |
| Peaking | 6000 Hz | 2.84 | 5.0 dB  |
| Peaking | 9168 Hz | 4.99 | -8.3 dB |
| Peaking | 17 Hz   | 0.19 | 6.2 dB  |
| Peaking | 39 Hz   | 0.7  | -6.7 dB |
| Peaking | 758 Hz  | 0.81 | -2.5 dB |
| Peaking | 1054 Hz | 1.84 | 4.8 dB  |
| Peaking | 1466 Hz | 5.84 | -2.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Panasonic%20RP%20HT600%20S/Panasonic%20RP%20HT600%20S.png)