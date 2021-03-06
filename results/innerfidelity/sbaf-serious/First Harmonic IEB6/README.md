# First Harmonic IEB6

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.7dB
GraphicEQ: 10 -84; 20 5.6; 22 4.8; 23 4.4; 25 3.8; 26 3.5; 28 3.0; 30 2.5; 32 2.1; 35 1.4; 37 1.0; 40 0.5; 42 0.2; 45 -0.2; 49 -0.8; 52 -1.2; 56 -1.6; 59 -2.0; 64 -2.5; 68 -2.9; 73 -3.4; 78 -3.8; 83 -4.2; 89 -4.6; 95 -4.9; 102 -5.3; 109 -5.4; 117 -5.6; 125 -5.7; 134 -6.0; 143 -6.0; 153 -6.0; 164 -6.0; 175 -6.0; 188 -5.9; 201 -5.8; 215 -5.5; 230 -5.3; 246 -5.1; 263 -4.9; 282 -4.5; 301 -4.2; 323 -3.9; 345 -3.5; 369 -3.1; 395 -2.8; 423 -2.3; 452 -2.0; 484 -1.6; 518 -1.4; 554 -0.8; 593 -0.3; 635 0.0; 679 0.0; 726 0.4; 777 0.7; 832 0.7; 890 0.5; 952 0.2; 1019 -0.1; 1090 -0.4; 1167 -0.7; 1248 -1.1; 1336 -1.6; 1429 -2.1; 1529 -2.6; 1636 -3.0; 1751 -3.2; 1873 -3.3; 2004 -3.5; 2145 -4.0; 2295 -3.8; 2455 -2.0; 2627 -3.0; 2811 -4.4; 3008 -5.3; 3219 -4.9; 3444 -3.6; 3685 -2.8; 3943 -2.7; 4219 -3.9; 4514 -5.0; 4830 -5.7; 5168 -6.6; 5530 -8.8; 5917 -11.6; 6331 -10.3; 6775 -6.5; 7249 -3.6; 7756 -1.4; 8299 -0.3; 8880 0.0; 9502 -0.0; 10167 -1.3; 10879 -2.8; 11640 -2.6; 12455 -1.1; 13327 -0.7; 14260 -2.1; 15258 -2.9; 16326 -0.6; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.657531203097645dB` and instead set Global volume in the UI for both channels to **-56**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `First Harmonic IEB6 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -5.2dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 20 Hz    | 1    | 5.6 dB   |
| Peaking | 149 Hz   | 0.57 | -6.5 dB  |
| Peaking | 1898 Hz  | 2.43 | -3.2 dB  |
| Peaking | 3069 Hz  | 2.99 | -4.0 dB  |
| Peaking | 5919 Hz  | 3.07 | -11.5 dB |
| Peaking | 313 Hz   | 2.34 | -0.7 dB  |
| Peaking | 765 Hz   | 2.2  | 1.7 dB   |
| Peaking | 4553 Hz  | 9.02 | -1.3 dB  |
| Peaking | 8650 Hz  | 2.57 | 3.5 dB   |
| Peaking | 11291 Hz | 0.93 | -2.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/First%20Harmonic%20IEB6/First%20Harmonic%20IEB6.png)