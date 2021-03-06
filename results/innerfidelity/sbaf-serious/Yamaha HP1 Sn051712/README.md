# Yamaha HP1 Sn051712

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 5.4; 22 5.2; 23 5.0; 25 4.7; 26 4.5; 28 4.1; 30 3.8; 32 3.5; 35 3.3; 37 3.1; 40 2.9; 42 2.7; 45 2.5; 49 2.2; 52 2.0; 56 1.9; 59 1.8; 64 1.7; 68 1.6; 73 1.4; 78 1.2; 83 1.1; 89 0.9; 95 0.6; 102 0.2; 109 -0.0; 117 -0.2; 125 -0.4; 134 -0.6; 143 -0.8; 153 -0.9; 164 -0.9; 175 -1.0; 188 -1.1; 201 -1.2; 215 -1.2; 230 -1.2; 246 -1.2; 263 -1.2; 282 -1.0; 301 -1.0; 323 -1.1; 345 -1.2; 369 -1.2; 395 -1.2; 423 -1.1; 452 -1.1; 484 -1.3; 518 -1.4; 554 -1.4; 593 -1.3; 635 -1.3; 679 -1.4; 726 -1.4; 777 -1.1; 832 -1.0; 890 -0.6; 952 -0.2; 1019 0.2; 1090 0.8; 1167 1.7; 1248 2.5; 1336 2.9; 1429 3.2; 1529 3.3; 1636 3.6; 1751 3.3; 1873 3.0; 2004 2.3; 2145 1.4; 2295 0.6; 2455 1.0; 2627 1.6; 2811 2.1; 3008 2.7; 3219 3.7; 3444 4.7; 3685 4.3; 3943 4.2; 4219 3.8; 4514 3.7; 4830 5.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.097714767088153dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Yamaha HP1 Sn051712 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 22 Hz   | 1.23 | 5.1 dB  |
| Peaking | 50 Hz   | 1.78 | 1.5 dB  |
| Peaking | 1575 Hz | 2.78 | 3.8 dB  |
| Peaking | 3561 Hz | 2.71 | 3.8 dB  |
| Peaking | 5631 Hz | 2.72 | 6.2 dB  |
| Peaking | 80 Hz   | 1.92 | 1.0 dB  |
| Peaking | 372 Hz  | 0.34 | -1.5 dB |
| Peaking | 1252 Hz | 4.05 | 1.7 dB  |
| Peaking | 6510 Hz | 7.8  | 2.1 dB  |
| Peaking | 7810 Hz | 2.62 | -1.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Yamaha%20HP1%20Sn051712/Yamaha%20HP1%20Sn051712.png)