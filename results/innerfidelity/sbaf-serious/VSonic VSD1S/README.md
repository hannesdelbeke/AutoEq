# VSonic VSD1S

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 1.9; 25 1.6; 28 1.2; 31 0.9; 34 0.6; 37 0.3; 41 0.0; 45 -0.2; 49 -0.5; 54 -0.7; 60 -1.1; 66 -1.5; 72 -1.8; 79 -2.2; 87 -2.6; 96 -2.8; 106 -3.1; 116 -3.2; 128 -3.4; 141 -3.6; 155 -3.6; 170 -3.6; 187 -3.5; 206 -3.3; 227 -3.0; 249 -2.8; 274 -2.5; 302 -2.1; 332 -1.7; 365 -1.3; 402 -0.9; 442 -0.5; 486 -0.2; 535 0.1; 588 0.6; 647 0.8; 712 0.8; 783 0.9; 861 0.5; 947 0.1; 1042 0.2; 1146 -0.3; 1261 -0.7; 1387 -1.3; 1526 -1.7; 1678 -1.8; 1846 -1.4; 2031 -0.6; 2234 0.3; 2457 2.1; 2703 3.9; 2973 5.9; 3270 6.0; 3597 6.0; 3957 6.0; 4353 3.4; 4788 0.9; 5267 1.7; 5793 5.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `VSonic VSD1S ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 20 Hz   | 1.2  | 2.5 dB  |
| Peaking | 145 Hz  | 0.7  | -3.9 dB |
| Peaking | 1752 Hz | 2.44 | -2.8 dB |
| Peaking | 3325 Hz | 1.94 | 6.9 dB  |
| Peaking | 6214 Hz | 5.82 | 5.5 dB  |
| Peaking | 274 Hz  | 2.69 | -0.6 dB |
| Peaking | 671 Hz  | 2.07 | 1.3 dB  |
| Peaking | 4739 Hz | 2.53 | 2.2 dB  |
| Peaking | 4857 Hz | 5.7  | -4.1 dB |
| Peaking | 8359 Hz | 3.31 | -0.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/VSonic%20VSD1S/VSonic%20VSD1S.png)