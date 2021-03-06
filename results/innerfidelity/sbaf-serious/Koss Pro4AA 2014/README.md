# Koss Pro4AA 2014

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 6.0; 102 6.0; 109 6.0; 117 6.0; 125 6.0; 134 6.0; 143 6.0; 153 6.0; 164 6.0; 175 5.8; 188 5.0; 201 4.2; 215 3.6; 230 2.7; 246 1.8; 263 0.9; 282 -0.1; 301 -0.9; 323 -1.6; 345 -2.3; 369 -3.2; 395 -3.9; 423 -4.3; 452 -4.5; 484 -4.6; 518 -4.9; 554 -4.5; 593 -3.7; 635 -3.3; 679 -2.9; 726 -2.2; 777 -1.5; 832 -1.0; 890 -0.6; 952 -0.1; 1019 0.1; 1090 0.3; 1167 0.1; 1248 -0.3; 1336 -1.2; 1429 -2.5; 1529 -3.9; 1636 -5.4; 1751 -6.7; 1873 -8.0; 2004 -9.4; 2145 -10.9; 2295 -11.5; 2455 -10.4; 2627 -8.3; 2811 -5.9; 3008 -2.5; 3219 0.3; 3444 2.4; 3685 2.9; 3943 2.2; 4219 0.5; 4514 -0.4; 4830 0.3; 5168 2.8; 5530 5.4; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.1; 9502 -1.0; 10167 -0.3; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000003dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss Pro4AA 2014 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 172 Hz  | 0.08 | 7.2 dB   |
| Peaking | 463 Hz  | 0.89 | -11.7 dB |
| Peaking | 2266 Hz | 1.38 | -15.1 dB |
| Peaking | 3478 Hz | 3.37 | 7.1 dB   |
| Peaking | 5974 Hz | 3.83 | 7.3 dB   |
| Peaking | 19 Hz   | 1.22 | 1.5 dB   |
| Peaking | 85 Hz   | 0.17 | -0.7 dB  |
| Peaking | 165 Hz  | 2.26 | 1.8 dB   |
| Peaking | 1160 Hz | 5.1  | 1.3 dB   |
| Peaking | 9430 Hz | 6.1  | -1.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Koss%20Pro4AA%202014/Koss%20Pro4AA%202014.png)