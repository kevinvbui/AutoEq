# Beyerdynamic DT 1350

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -1.3; 22 -1.4; 23 -1.4; 25 -1.5; 26 -1.5; 28 -1.5; 30 -1.6; 32 -1.7; 35 -1.7; 37 -1.8; 40 -1.8; 42 -1.8; 45 -1.8; 49 -1.9; 52 -1.8; 56 -1.6; 59 -1.6; 64 -2.0; 68 -2.2; 73 -2.3; 78 -2.5; 83 -2.3; 89 -1.8; 95 -1.3; 102 -0.7; 109 -0.7; 117 -1.3; 125 -1.5; 134 -0.7; 143 -0.4; 153 -0.6; 164 -1.0; 175 -2.3; 188 -3.1; 201 -3.5; 215 -3.7; 230 -3.8; 246 -3.9; 263 -4.0; 282 -3.5; 301 -3.4; 323 -4.0; 345 -4.3; 369 -4.2; 395 -3.9; 423 -3.9; 452 -4.2; 484 -4.2; 518 -3.9; 554 -3.6; 593 -3.1; 635 -2.8; 679 -2.2; 726 -1.5; 777 -1.0; 832 -1.0; 890 -0.8; 952 -0.4; 1019 0.0; 1090 0.4; 1167 0.8; 1248 1.1; 1336 1.1; 1429 0.9; 1529 0.6; 1636 0.3; 1751 0.0; 1873 0.3; 2004 1.1; 2145 2.4; 2295 4.1; 2455 5.8; 2627 6.0; 2811 6.0; 3008 6.0; 3219 6.0; 3444 6.0; 3685 6.0; 3943 5.2; 4219 2.8; 4514 1.5; 4830 2.7; 5168 5.3; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 -0.5; 8299 -5.6; 8880 -9.1; 9502 -8.3; 10167 -2.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999996126dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic DT 1350 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 44 Hz    | 0.66 | -2.0 dB  |
| Peaking | 362 Hz   | 0.78 | -4.5 dB  |
| Peaking | 2996 Hz  | 1.64 | 6.6 dB   |
| Peaking | 6062 Hz  | 2.76 | 6.2 dB   |
| Peaking | 8991 Hz  | 4.64 | -11.4 dB |
| Peaking | 151 Hz   | 4.13 | 1.5 dB   |
| Peaking | 199 Hz   | 3.76 | -1.4 dB  |
| Peaking | 1228 Hz  | 2.88 | 1.2 dB   |
| Peaking | 1820 Hz  | 5.44 | -1.7 dB  |
| Peaking | 10885 Hz | 9.54 | 1.8 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Beyerdynamic%20DT%201350/Beyerdynamic%20DT%201350.png)