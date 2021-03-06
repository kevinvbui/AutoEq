# Enigmatic Audio Paradox

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 10 -84; 20 4.2; 22 3.9; 23 3.8; 25 3.5; 26 3.4; 28 3.1; 30 2.9; 32 2.8; 35 2.6; 37 2.5; 40 2.4; 42 2.4; 45 2.4; 49 2.3; 52 2.2; 56 1.9; 59 1.5; 64 1.2; 68 1.2; 73 1.1; 78 1.1; 83 1.0; 89 0.7; 95 -0.1; 102 -1.2; 109 -2.1; 117 -2.7; 125 -3.2; 134 -3.4; 143 -3.5; 153 -3.4; 164 -2.8; 175 -3.5; 188 -3.9; 201 -3.9; 215 -3.8; 230 -3.6; 246 -3.5; 263 -3.4; 282 -3.1; 301 -2.8; 323 -2.5; 345 -1.6; 369 -0.3; 395 0.2; 423 0.5; 452 0.7; 484 0.7; 518 0.7; 554 0.9; 593 1.2; 635 2.1; 679 2.4; 726 1.8; 777 1.7; 832 1.7; 890 1.1; 952 0.4; 1019 -0.1; 1090 -0.4; 1167 -0.4; 1248 -0.3; 1336 -0.4; 1429 -0.2; 1529 0.0; 1636 0.6; 1751 0.8; 1873 1.4; 2004 2.3; 2145 3.2; 2295 4.1; 2455 4.9; 2627 5.6; 2811 6.0; 3008 6.0; 3219 5.8; 3444 5.1; 3685 4.4; 3943 4.3; 4219 4.2; 4514 4.7; 4830 5.9; 5168 6.0; 5530 6.0; 5917 5.9; 6331 5.5; 6775 3.9; 7249 1.3; 7756 0.3; 8299 -0.2; 8880 -2.3; 9502 -1.8; 10167 0.0; 10879 0.0; 11640 0.0; 12455 0.0; 13327 0.0; 14260 0.0; 15258 0.0; 16326 0.0; 17469 0.0; 18692 0.0; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.099999999918781dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Enigmatic Audio Paradox ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 24 Hz   |  0.15 | 3.7 dB  |
| Peaking | 173 Hz  |  0.64 | -5.8 dB |
| Peaking | 586 Hz  |  1.45 | 2.7 dB  |
| Peaking | 2912 Hz |  1.93 | 6.0 dB  |
| Peaking | 5463 Hz |  2.56 | 6.1 dB  |
| Peaking | 392 Hz  |  9.66 | 1.1 dB  |
| Peaking | 1319 Hz |  1.56 | -3.3 dB |
| Peaking | 1336 Hz |  0.93 | 2.0 dB  |
| Peaking | 6488 Hz | 10.15 | 2.0 dB  |
| Peaking | 9015 Hz |  4.82 | -3.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Enigmatic%20Audio%20Paradox/Enigmatic%20Audio%20Paradox.png)