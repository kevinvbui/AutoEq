# Shure SE215

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.5dB
GraphicEQ: 10 -84; 20 -3.3; 22 -3.5; 23 -3.6; 25 -3.7; 26 -3.8; 28 -3.9; 30 -4.0; 32 -4.0; 35 -4.2; 37 -4.2; 40 -4.3; 42 -4.4; 45 -4.5; 49 -4.6; 52 -4.7; 56 -4.9; 59 -5.0; 64 -5.2; 68 -5.3; 73 -5.5; 78 -5.7; 83 -5.9; 89 -6.1; 95 -6.3; 102 -6.4; 109 -6.6; 117 -6.7; 125 -6.8; 134 -6.8; 143 -6.8; 153 -6.8; 164 -6.7; 175 -6.6; 188 -6.5; 201 -6.3; 215 -6.1; 230 -5.9; 246 -5.6; 263 -5.3; 282 -5.0; 301 -4.7; 323 -4.3; 345 -3.8; 369 -3.5; 395 -3.1; 423 -2.8; 452 -2.4; 484 -2.0; 518 -1.7; 554 -1.3; 593 -0.9; 635 -0.6; 679 -0.3; 726 -0.0; 777 0.2; 832 0.4; 890 0.4; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.8; 1248 -0.8; 1336 -0.5; 1429 -0.6; 1529 -0.7; 1636 -0.8; 1751 -1.0; 1873 -1.3; 2004 -1.4; 2145 -1.5; 2295 -1.1; 2455 -0.3; 2627 1.0; 2811 2.4; 3008 3.5; 3219 4.2; 3444 4.3; 3685 3.9; 3943 2.9; 4219 1.3; 4514 -1.2; 4830 -3.6; 5168 -2.9; 5530 0.6; 5917 3.8; 6331 5.4; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 -0.1; 9502 -0.0; 10167 0.0; 10879 0.0; 11640 -0.9; 12455 -2.8; 13327 -4.6; 14260 -7.0; 15258 -9.9; 16326 -12.0; 17469 -12.2; 18692 -11.2; 20000 -9.3
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.503106883782721dB` and instead set Global volume in the UI for both channels to **-55**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shure SE215 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.1dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 51 Hz    | 0.26 | -4.0 dB  |
| Peaking | 181 Hz   | 0.63 | -4.5 dB  |
| Peaking | 3352 Hz  | 4.48 | 4.9 dB   |
| Peaking | 10726 Hz | 0.68 | 6.8 dB   |
| Peaking | 16967 Hz | 0.55 | -14.9 dB |
| Peaking | 797 Hz   | 3.06 | 1.3 dB   |
| Peaking | 2037 Hz  | 2.21 | -2.1 dB  |
| Peaking | 5041 Hz  | 3.76 | -10.2 dB |
| Peaking | 6254 Hz  | 1.38 | 10.8 dB  |
| Peaking | 7706 Hz  | 1.75 | -7.1 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_in-ear_2017-1/Shure%20SE215/Shure%20SE215.png)