# Philips L2

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.6dB
GraphicEQ: 10 -84; 20 -3.5; 22 -4.1; 23 -4.4; 25 -4.8; 26 -5.0; 28 -5.2; 30 -5.4; 32 -5.6; 35 -5.8; 37 -5.9; 40 -6.0; 42 -6.1; 45 -6.1; 49 -6.1; 52 -6.1; 56 -6.0; 59 -6.0; 64 -5.9; 68 -5.8; 73 -5.6; 78 -5.5; 83 -5.4; 89 -5.2; 95 -5.1; 102 -5.1; 109 -5.0; 117 -5.1; 125 -5.3; 134 -5.2; 143 -4.8; 153 -4.6; 164 -4.0; 175 -3.9; 188 -4.0; 201 -3.9; 215 -3.7; 230 -3.4; 246 -3.3; 263 -3.1; 282 -2.7; 301 -2.3; 323 -2.1; 345 -1.9; 369 -1.6; 395 -1.4; 423 -1.0; 452 -0.6; 484 -0.5; 518 -0.1; 554 0.3; 593 0.8; 635 1.1; 679 1.1; 726 1.0; 777 0.9; 832 0.6; 890 0.2; 952 0.0; 1019 -0.1; 1090 0.0; 1167 0.3; 1248 -0.7; 1336 -2.1; 1429 -3.5; 1529 -4.8; 1636 -5.9; 1751 -6.3; 1873 -6.7; 2004 -6.8; 2145 -6.5; 2295 -6.4; 2455 -6.3; 2627 -5.5; 2811 -4.9; 3008 -3.9; 3219 -2.7; 3444 -1.5; 3685 -0.9; 3943 0.2; 4219 1.6; 4514 3.1; 4830 4.3; 5168 5.5; 5530 4.1; 5917 0.4; 6331 -1.7; 6775 -2.7; 7249 -3.0; 7756 -2.3; 8299 -1.7; 8880 -1.1; 9502 -0.3; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 -1.7; 18692 -3.2; 20000 -2.4
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.582667950473633dB` and instead set Global volume in the UI for both channels to **-55**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Philips L2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.8dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -6.0dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 47 Hz    | 0.43 | -5.9 dB |
| Peaking | 172 Hz   | 0.98 | -2.6 dB |
| Peaking | 2137 Hz  | 1.6  | -7.5 dB |
| Peaking | 4989 Hz  | 5.04 | 6.7 dB  |
| Peaking | 675 Hz   | 3.1  | 1.6 dB  |
| Peaking | 1339 Hz  | 1.45 | 2.7 dB  |
| Peaking | 1541 Hz  | 3.07 | -4.0 dB |
| Peaking | 7184 Hz  | 4.21 | -3.5 dB |
| Peaking | 19009 Hz | 2.27 | -3.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Philips%20L2/Philips%20L2.png)