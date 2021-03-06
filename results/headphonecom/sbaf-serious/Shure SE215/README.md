# Shure SE215

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.8dB
GraphicEQ: 10 -84; 20 -5.5; 22 -5.5; 23 -5.5; 25 -5.5; 26 -5.5; 28 -5.6; 30 -5.6; 32 -5.6; 35 -5.7; 37 -5.7; 40 -5.8; 42 -5.8; 45 -5.9; 49 -6.1; 52 -6.2; 56 -6.4; 59 -6.5; 64 -6.6; 68 -6.8; 73 -7.0; 78 -7.0; 83 -7.2; 89 -7.3; 95 -7.4; 102 -7.4; 109 -7.5; 117 -7.5; 125 -7.5; 134 -7.5; 143 -7.5; 153 -7.5; 164 -7.4; 175 -7.2; 188 -7.1; 201 -6.9; 215 -6.6; 230 -6.3; 246 -6.1; 263 -5.7; 282 -5.3; 301 -5.0; 323 -4.5; 345 -4.1; 369 -3.6; 395 -3.2; 423 -2.8; 452 -2.4; 484 -2.0; 518 -1.5; 554 -1.1; 593 -0.7; 635 -0.3; 679 -0.0; 726 0.3; 777 0.4; 832 0.5; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.4; 1248 -0.8; 1336 -2.0; 1429 -2.8; 1529 -3.6; 1636 -4.2; 1751 -4.7; 1873 -5.2; 2004 -5.5; 2145 -5.7; 2295 -5.4; 2455 -4.4; 2627 -2.7; 2811 -0.7; 3008 1.3; 3219 3.2; 3444 4.3; 3685 4.2; 3943 2.4; 4219 -1.0; 4514 -4.9; 4830 -7.5; 5168 -3.9; 5530 1.5; 5917 5.2; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 -0.4; 10167 -0.2; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.832552328288438dB` and instead set Global volume in the UI for both channels to **-58**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SE215 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -0.1dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 33 Hz    | 0.26 | -5.3 dB  |
| Peaking | 134 Hz   | 0.76 | -4.5 dB  |
| Peaking | 263 Hz   | 1.34 | -2.9 dB  |
| Peaking | 1978 Hz  | 2.73 | -6.3 dB  |
| Peaking | 24000 Hz | 2.49 | -3.4 dB  |
| Peaking | 800 Hz   | 3.17 | 1.4 dB   |
| Peaking | 2459 Hz  | 4.47 | -2.9 dB  |
| Peaking | 3566 Hz  | 2.77 | 6.7 dB   |
| Peaking | 4788 Hz  | 4.09 | -10.5 dB |
| Peaking | 6062 Hz  | 4.09 | 7.9 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Shure%20SE215/Shure%20SE215.png)