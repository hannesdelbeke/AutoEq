# Beyerdynamic T1 sn3964

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.9dB
GraphicEQ: 21 0.0; 23 3.3; 25 2.9; 28 2.4; 31 2.1; 34 1.8; 37 1.5; 41 1.2; 45 0.9; 49 0.7; 54 0.7; 60 1.0; 66 0.9; 72 -0.1; 79 -0.7; 87 -1.2; 96 -1.6; 106 -1.9; 116 -2.1; 128 -2.4; 141 -2.7; 155 -2.8; 170 -2.9; 187 -3.0; 206 -3.0; 227 -2.9; 249 -2.8; 274 -2.7; 302 -2.5; 332 -2.3; 365 -2.1; 402 -1.8; 442 -1.6; 486 -1.4; 535 -1.3; 588 -0.8; 647 -0.3; 712 -0.0; 783 0.1; 861 -0.4; 947 -0.3; 1042 0.2; 1146 0.9; 1261 0.2; 1387 0.0; 1526 0.2; 1678 -0.4; 1846 -1.2; 2031 -1.0; 2234 -1.8; 2457 -1.5; 2703 -1.6; 2973 -0.6; 3270 0.7; 3597 0.2; 3957 -1.1; 4353 -2.1; 4788 -0.4; 5267 4.8; 5793 -1.1; 6373 -4.4; 7010 1.0; 7711 -4.7; 8482 -8.3; 9330 -6.0; 10263 -1.0; 11289 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.9dB` and instead set Global volume in the UI for both channels to **-49**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic T1 sn3964 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -5.4dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 187 Hz  |  0.61 | -3.3 dB |
| Peaking | 2384 Hz |  3.11 | -1.8 dB |
| Peaking | 5251 Hz | 13.49 | 5.9 dB  |
| Peaking | 8554 Hz |  4.07 | -9.0 dB |
| Peaking | 16 Hz   |  0.63 | 4.3 dB  |
| Peaking | 65 Hz   |  4.02 | 1.3 dB  |
| Peaking | 4442 Hz |  4.25 | -4.1 dB |
| Peaking | 5411 Hz |  1.37 | 2.7 dB  |
| Peaking | 6157 Hz |  9.43 | -6.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beyerdynamic%20T1%20sn3964/Beyerdynamic%20T1%20sn3964.png)