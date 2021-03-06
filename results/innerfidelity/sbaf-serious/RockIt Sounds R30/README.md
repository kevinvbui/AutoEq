# RockIt Sounds R30

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 5.9; 35 5.8; 37 5.6; 40 5.3; 42 5.2; 45 4.9; 49 4.6; 52 4.4; 56 4.1; 59 3.9; 64 3.6; 68 3.3; 73 2.9; 78 2.7; 83 2.3; 89 1.9; 95 1.6; 102 1.3; 109 1.2; 117 1.0; 125 0.6; 134 0.4; 143 0.2; 153 0.0; 164 -0.2; 175 -0.3; 188 -0.4; 201 -0.5; 215 -0.6; 230 -0.5; 246 -0.6; 263 -0.6; 282 -0.6; 301 -0.5; 323 -0.5; 345 -0.4; 369 -0.4; 395 -0.3; 423 -0.1; 452 0.0; 484 0.0; 518 0.2; 554 0.3; 593 0.6; 635 0.7; 679 0.6; 726 0.7; 777 0.8; 832 0.7; 890 0.5; 952 0.2; 1019 -0.0; 1090 -0.3; 1167 -0.5; 1248 -0.8; 1336 -1.2; 1429 -1.5; 1529 -1.9; 1636 -2.0; 1751 -1.9; 1873 -1.5; 2004 -1.0; 2145 -0.4; 2295 0.5; 2455 1.9; 2627 3.3; 2811 4.8; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 6.0; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000001dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `RockIt Sounds R30 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 26 Hz   | 0.35 | 6.2 dB  |
| Peaking | 183 Hz  | 0.55 | -1.3 dB |
| Peaking | 712 Hz  | 1.47 | 1.0 dB  |
| Peaking | 1768 Hz | 1.55 | -4.2 dB |
| Peaking | 3875 Hz | 0.93 | 7.4 dB  |
| Peaking | 2270 Hz | 5.94 | -0.6 dB |
| Peaking | 2944 Hz | 4.88 | 1.5 dB  |
| Peaking | 3929 Hz | 3.16 | -1.1 dB |
| Peaking | 6293 Hz | 2.56 | 5.0 dB  |
| Peaking | 7399 Hz | 1.55 | -3.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/RockIt%20Sounds%20R30/RockIt%20Sounds%20R30.png)