# Denon AH-D5000 JMoney Pads

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.6dB
GraphicEQ: 10 -84; 20 5.5; 22 4.1; 23 3.5; 25 2.5; 26 2.1; 28 1.3; 30 0.8; 32 0.4; 35 -0.1; 37 -0.3; 40 -0.4; 42 -0.5; 45 -0.5; 49 -0.6; 52 -0.6; 56 -0.6; 59 -0.6; 64 -0.6; 68 -0.6; 73 -0.6; 78 -0.8; 83 -0.9; 89 -1.2; 95 -1.3; 102 -1.5; 109 -1.5; 117 -1.4; 125 -1.7; 134 -1.7; 143 -1.7; 153 -1.9; 164 -1.9; 175 -1.8; 188 -1.8; 201 -1.7; 215 -1.7; 230 -1.5; 246 -1.6; 263 -1.5; 282 -1.3; 301 -1.1; 323 -1.0; 345 -1.1; 369 -1.0; 395 -0.7; 423 -0.0; 452 0.3; 484 0.3; 518 0.7; 554 1.0; 593 1.0; 635 0.6; 679 0.0; 726 -0.7; 777 -1.8; 832 -2.8; 890 -0.6; 952 0.6; 1019 -0.3; 1090 -0.8; 1167 -1.1; 1248 -1.3; 1336 -1.6; 1429 -1.9; 1529 -2.4; 1636 -2.9; 1751 -3.0; 1873 -3.0; 2004 -3.1; 2145 -3.1; 2295 -3.5; 2455 -3.2; 2627 -1.9; 2811 -1.1; 3008 -2.2; 3219 -3.0; 3444 -3.6; 3685 -4.0; 3943 -4.7; 4219 -5.9; 4514 -5.5; 4830 -5.9; 5168 -6.5; 5530 -5.8; 5917 -3.6; 6331 -2.8; 6775 -4.5; 7249 -5.8; 7756 -6.0; 8299 -5.3; 8880 -3.5; 9502 -1.4; 10167 -0.6; 10879 -1.8; 11640 -4.0; 12455 -5.5; 13327 -5.7; 14260 -4.2; 15258 -2.1; 16326 -1.2; 17469 -1.9; 18692 -1.3; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-5.615965023853878dB` and instead set Global volume in the UI for both channels to **-56**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Denon AH-D5000 JMoney Pads ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.2dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 22 Hz    | 3.27 | 5.4 dB  |
| Peaking | 1785 Hz  | 1.82 | -2.3 dB |
| Peaking | 5336 Hz  | 0.85 | -5.5 dB |
| Peaking | 13242 Hz | 2.86 | -5.3 dB |
| Peaking | 21869 Hz | 1.45 | -4.3 dB |
| Peaking | 153 Hz   | 0.77 | -1.9 dB |
| Peaking | 2833 Hz  | 7.1  | 1.9 dB  |
| Peaking | 6254 Hz  | 4.82 | 5.1 dB  |
| Peaking | 7803 Hz  | 1.18 | -3.7 dB |
| Peaking | 9880 Hz  | 3.42 | 4.5 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Denon%20AH-D5000%20JMoney%20Pads/Denon%20AH-D5000%20JMoney%20Pads.png)