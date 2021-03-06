# Cardas EM5813

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -6.3; 23 -6.3; 25 -6.3; 28 -6.4; 31 -6.4; 34 -6.5; 37 -6.6; 41 -6.7; 45 -6.8; 49 -6.9; 54 -7.1; 60 -7.4; 66 -7.6; 72 -7.9; 79 -8.2; 87 -8.5; 96 -8.8; 106 -9.0; 116 -9.2; 128 -9.4; 141 -9.5; 155 -9.5; 170 -9.5; 187 -9.4; 206 -9.3; 227 -9.0; 249 -8.8; 274 -8.4; 302 -8.1; 332 -7.6; 365 -7.2; 402 -6.8; 442 -6.2; 486 -5.8; 535 -5.2; 588 -4.3; 647 -3.8; 712 -3.4; 783 -2.9; 861 -1.7; 947 -0.1; 1042 -0.3; 1146 -0.4; 1261 -0.6; 1387 -1.2; 1526 -1.5; 1678 -1.6; 1846 -1.3; 2031 -1.7; 2234 -2.5; 2457 -4.2; 2703 -4.6; 2973 -0.3; 3270 2.0; 3597 1.8; 3957 -1.1; 4353 -5.7; 4788 -3.1; 5267 3.6; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Cardas EM5813 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 21 Hz   | 0.2  | -5.8 dB |
| Peaking | 124 Hz  | 0.66 | -4.0 dB |
| Peaking | 294 Hz  | 0.55 | -6.1 dB |
| Peaking | 4498 Hz | 6.42 | -8.0 dB |
| Peaking | 5846 Hz | 3.47 | 7.4 dB  |
| Peaking | 1019 Hz | 2.49 | 2.7 dB  |
| Peaking | 1206 Hz | 0.62 | -1.0 dB |
| Peaking | 2603 Hz | 4.33 | -5.3 dB |
| Peaking | 3323 Hz | 4.31 | 4.0 dB  |
| Peaking | 8210 Hz | 5.16 | -0.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Cardas%20EM5813/Cardas%20EM5813.png)