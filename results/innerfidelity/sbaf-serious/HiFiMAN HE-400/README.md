# HiFiMAN HE-400

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 6.0; 22 6.0; 23 6.0; 25 6.0; 26 6.0; 28 6.0; 30 6.0; 32 6.0; 35 6.0; 37 6.0; 40 6.0; 42 6.0; 45 6.0; 49 6.0; 52 6.0; 56 6.0; 59 6.0; 64 6.0; 68 6.0; 73 6.0; 78 6.0; 83 6.0; 89 6.0; 95 5.8; 102 5.6; 109 5.6; 117 5.4; 125 5.2; 134 5.1; 143 4.9; 153 4.8; 164 4.6; 175 4.5; 188 4.4; 201 4.5; 215 5.3; 230 4.7; 246 4.2; 263 4.4; 282 5.6; 301 4.9; 323 4.3; 345 4.1; 369 4.2; 395 4.3; 423 4.1; 452 3.8; 484 4.0; 518 4.7; 554 5.5; 593 5.7; 635 4.8; 679 4.0; 726 3.3; 777 3.0; 832 1.9; 890 0.6; 952 0.2; 1019 0.5; 1090 3.0; 1167 1.8; 1248 2.4; 1336 3.9; 1429 5.3; 1529 5.7; 1636 5.6; 1751 5.8; 1873 6.0; 2004 5.9; 2145 5.0; 2295 5.9; 2455 6.0; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 6.0; 4219 6.0; 4514 5.3; 4830 5.6; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.9; 9502 -0.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 -0.6; 14260 -0.1; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.100000000000002dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiFiMAN HE-400 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 42 Hz    | 0.2  | 6.2 dB  |
| Peaking | 311 Hz   | 1.31 | 2.4 dB  |
| Peaking | 580 Hz   | 4.1  | 3.8 dB  |
| Peaking | 3731 Hz  | 0.43 | 6.9 dB  |
| Peaking | 9040 Hz  | 1.51 | -4.1 dB |
| Peaking | 961 Hz   | 5.65 | -2.9 dB |
| Peaking | 1608 Hz  | 3.33 | 1.9 dB  |
| Peaking | 5302 Hz  | 0.98 | -1.2 dB |
| Peaking | 5939 Hz  | 3.43 | 2.9 dB  |
| Peaking | 13698 Hz | 5.2  | -1.1 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/HiFiMAN%20HE-400/HiFiMAN%20HE-400.png)