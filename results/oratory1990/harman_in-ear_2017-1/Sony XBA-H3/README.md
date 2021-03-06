# Sony XBA-H3

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 0.4; 22 0.2; 23 0.1; 25 -0.0; 26 -0.1; 28 -0.2; 30 -0.3; 32 -0.4; 35 -0.6; 37 -0.7; 40 -0.8; 42 -0.9; 45 -1.0; 49 -1.1; 52 -1.3; 56 -1.4; 59 -1.6; 64 -1.8; 68 -2.0; 73 -2.2; 78 -2.4; 83 -2.6; 89 -2.9; 95 -3.1; 102 -3.3; 109 -3.5; 117 -3.6; 125 -3.8; 134 -3.8; 143 -3.9; 153 -3.9; 164 -3.8; 175 -3.7; 188 -3.6; 201 -3.4; 215 -3.2; 230 -2.9; 246 -2.7; 263 -2.4; 282 -2.1; 301 -1.8; 323 -1.5; 345 -1.2; 369 -1.0; 395 -0.8; 423 -0.5; 452 -0.3; 484 -0.1; 518 0.0; 554 0.2; 593 0.4; 635 0.5; 679 0.6; 726 0.7; 777 0.7; 832 0.6; 890 0.3; 952 0.2; 1019 -0.1; 1090 -0.3; 1167 -0.6; 1248 -0.8; 1336 -0.7; 1429 -0.5; 1529 -0.2; 1636 0.1; 1751 0.5; 1873 1.3; 2004 2.4; 2145 4.1; 2295 5.7; 2455 6.0; 2627 6.0; 2811 6.0; 3008 5.9; 3219 4.4; 3444 3.0; 3685 2.5; 3943 2.3; 4219 1.1; 4514 -1.1; 4830 -2.4; 5168 -1.8; 5530 0.6; 5917 3.3; 6331 5.1; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.0; 8880 -2.7; 9502 -6.1; 10167 -7.4; 10879 -6.0; 11640 -3.9; 12455 -4.1; 13327 -7.7; 14260 -12.5; 15258 -16.5; 16326 -19.3; 17469 -20.4; 18692 -18.1; 20000 -11.2
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999999269dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony XBA-H3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 140 Hz   | 0.71 | -4.0 dB  |
| Peaking | 2686 Hz  | 2.32 | 7.1 dB   |
| Peaking | 6522 Hz  | 5.16 | 6.9 dB   |
| Peaking | 16674 Hz | 1.05 | -17.6 dB |
| Peaking | 18895 Hz | 1.55 | -8.0 dB  |
| Peaking | 1440 Hz  | 1.6  | -2.3 dB  |
| Peaking | 2386 Hz  | 0.23 | 1.1 dB   |
| Peaking | 4911 Hz  | 5.76 | -4.2 dB  |
| Peaking | 10036 Hz | 5.84 | -4.7 dB  |
| Peaking | 12256 Hz | 5.87 | 3.8 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_in-ear_2017-1/Sony%20XBA-H3/Sony%20XBA-H3.png)