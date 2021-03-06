# Onkyo ES-FC300

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -4.4; 22 -4.6; 23 -4.7; 25 -4.9; 26 -4.9; 28 -5.0; 30 -5.0; 32 -5.0; 35 -4.9; 37 -5.0; 40 -5.1; 42 -5.2; 45 -5.3; 49 -5.5; 52 -5.5; 56 -5.3; 59 -5.1; 64 -4.7; 68 -4.3; 73 -4.0; 78 -4.6; 83 -5.3; 89 -5.7; 95 -5.9; 102 -5.4; 109 -5.2; 117 -5.5; 125 -5.9; 134 -5.8; 143 -5.8; 153 -5.5; 164 -4.7; 175 -4.6; 188 -4.0; 201 -3.0; 215 -2.2; 230 -1.3; 246 -0.4; 263 -0.0; 282 -0.4; 301 -1.4; 323 -2.1; 345 -2.5; 369 -2.8; 395 -3.0; 423 -2.9; 452 -2.7; 484 -2.6; 518 -2.4; 554 -2.2; 593 -1.8; 635 -1.6; 679 -1.5; 726 -1.2; 777 -0.8; 832 -0.6; 890 -0.4; 952 -0.1; 1019 0.0; 1090 0.2; 1167 0.5; 1248 0.7; 1336 0.7; 1429 0.6; 1529 0.3; 1636 0.1; 1751 0.0; 1873 0.2; 2004 0.5; 2145 0.6; 2295 0.7; 2455 0.9; 2627 0.8; 2811 0.5; 3008 1.3; 3219 1.7; 3444 1.9; 3685 2.9; 3943 5.3; 4219 5.4; 4514 5.4; 4830 6.0; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 0.0; 8880 0.0; 9502 0.0; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099856830925145dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Onkyo ES-FC300 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 14 Hz   | 0.5  | -3.6 dB |
| Peaking | 53 Hz   | 0.59 | -4.0 dB |
| Peaking | 135 Hz  | 1.52 | -4.4 dB |
| Peaking | 462 Hz  | 1.87 | -2.7 dB |
| Peaking | 5037 Hz | 1.7  | 6.8 dB  |
| Peaking | 259 Hz  | 6.98 | 1.9 dB  |
| Peaking | 1263 Hz | 4.99 | 0.9 dB  |
| Peaking | 6206 Hz | 6    | 1.8 dB  |
| Peaking | 6659 Hz | 5.31 | 2.2 dB  |
| Peaking | 7407 Hz | 1.87 | -2.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Onkyo%20ES-FC300/Onkyo%20ES-FC300.png)