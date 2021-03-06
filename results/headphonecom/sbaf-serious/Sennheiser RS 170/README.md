# Sennheiser RS 170

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.8dB
GraphicEQ: 21 0.0; 23 5.2; 25 4.3; 28 3.1; 31 2.2; 34 1.4; 37 0.7; 41 -0.2; 45 -0.9; 49 -1.4; 54 -2.1; 60 -2.6; 66 -3.0; 72 -3.6; 79 -3.9; 87 -3.8; 96 -3.4; 106 -3.5; 116 -4.4; 128 -5.3; 141 -5.9; 155 -6.1; 170 -5.5; 187 -6.0; 206 -5.6; 227 -4.5; 249 -3.8; 274 -3.4; 302 -2.7; 332 -1.9; 365 -1.4; 402 -1.6; 442 -1.8; 486 -1.7; 535 -0.9; 588 -0.2; 647 0.5; 712 0.7; 783 1.6; 861 2.3; 947 0.5; 1042 0.1; 1146 0.5; 1261 -1.5; 1387 -2.7; 1526 -4.2; 1678 -5.7; 1846 -1.4; 2031 -3.4; 2234 -4.3; 2457 -4.4; 2703 -4.2; 2973 -3.8; 3270 -3.6; 3597 -3.2; 3957 -1.6; 4353 1.9; 4788 6.0; 5267 1.9; 5793 2.2; 6373 -0.1; 7010 0.7; 7711 0.3; 8482 -2.0; 9330 -4.9; 10263 -3.3; 11289 -0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.8dB` and instead set Global volume in the UI for both channels to **-67**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser RS 170 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.2dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 21 Hz   | 1.94 | 6.1 dB  |
| Peaking | 147 Hz  | 0.74 | -6.0 dB |
| Peaking | 1627 Hz | 6.93 | -4.0 dB |
| Peaking | 4107 Hz | 0.87 | -9.7 dB |
| Peaking | 4777 Hz | 2.17 | 14.4 dB |
| Peaking | 65 Hz   | 3.5  | -1.2 dB |
| Peaking | 826 Hz  | 3.03 | 3.1 dB  |
| Peaking | 2295 Hz | 7.07 | -1.5 dB |
| Peaking | 7507 Hz | 5.53 | 2.3 dB  |
| Peaking | 9472 Hz | 5.68 | -4.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20RS%20170/Sennheiser%20RS%20170.png)