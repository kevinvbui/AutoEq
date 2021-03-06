# Klipsch Reference On Ear

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 -4.1; 22 -4.3; 23 -4.4; 25 -4.5; 26 -4.6; 28 -4.6; 30 -4.7; 32 -4.8; 35 -4.8; 37 -4.9; 40 -4.9; 42 -4.9; 45 -4.9; 49 -4.9; 52 -4.9; 56 -4.8; 59 -4.8; 64 -4.9; 68 -5.0; 73 -5.2; 78 -5.3; 83 -5.4; 89 -5.5; 95 -5.6; 102 -5.8; 109 -5.7; 117 -5.9; 125 -6.1; 134 -6.2; 143 -6.1; 153 -6.3; 164 -6.3; 175 -6.1; 188 -6.4; 201 -6.6; 215 -6.5; 230 -6.3; 246 -6.2; 263 -6.0; 282 -5.7; 301 -5.4; 323 -5.3; 345 -5.3; 369 -5.5; 395 -5.1; 423 -4.5; 452 -4.6; 484 -5.1; 518 -4.9; 554 -4.6; 593 -3.9; 635 -3.6; 679 -3.4; 726 -2.9; 777 -2.2; 832 -1.7; 890 -1.1; 952 -0.5; 1019 0.2; 1090 0.9; 1167 1.5; 1248 2.0; 1336 1.8; 1429 1.6; 1529 1.7; 1636 1.7; 1751 1.8; 1873 1.8; 2004 2.0; 2145 2.6; 2295 2.6; 2455 2.7; 2627 2.4; 2811 1.9; 3008 1.5; 3219 1.0; 3444 0.7; 3685 0.7; 3943 0.6; 4219 0.8; 4514 1.3; 4830 3.2; 5168 5.6; 5530 5.8; 5917 3.0; 6331 1.7; 6775 1.7; 7249 0.3; 7756 -1.8; 8299 -3.6; 8880 -4.4; 9502 -3.8; 10167 -1.5; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.140847201398657dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Klipsch Reference On Ear ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.1dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -2.4dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 39 Hz   | 0.27 | -4.0 dB |
| Peaking | 221 Hz  | 0.52 | -5.0 dB |
| Peaking | 606 Hz  | 1.01 | -4.1 dB |
| Peaking | 1416 Hz | 0.35 | 3.1 dB  |
| Peaking | 27 Hz   | 1.31 | -0.6 dB |
| Peaking | 2453 Hz | 5.31 | 0.9 dB  |
| Peaking | 4121 Hz | 1.69 | -2.1 dB |
| Peaking | 5351 Hz | 3.77 | 6.3 dB  |
| Peaking | 8849 Hz | 3.8  | -5.4 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Klipsch%20Reference%20On%20Ear/Klipsch%20Reference%20On%20Ear.png)