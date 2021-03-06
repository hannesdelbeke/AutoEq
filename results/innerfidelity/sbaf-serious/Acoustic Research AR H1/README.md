# Acoustic Research AR H1

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 3.8; 25 3.6; 28 3.4; 31 3.3; 34 3.2; 37 3.2; 41 3.1; 45 3.1; 49 3.0; 54 2.8; 60 2.7; 66 2.5; 72 2.3; 79 2.0; 87 1.6; 96 1.1; 106 0.7; 116 0.3; 128 -0.2; 141 -0.6; 155 -0.9; 170 -1.0; 187 -1.2; 206 -1.0; 227 -0.0; 249 0.0; 274 -0.4; 302 -0.8; 332 -1.2; 365 -1.8; 402 -1.5; 442 -0.9; 486 0.6; 535 -0.7; 588 -1.3; 647 -2.3; 712 0.4; 783 2.6; 861 0.5; 947 -0.2; 1042 0.1; 1146 -0.0; 1261 0.1; 1387 0.3; 1526 1.2; 1678 -0.7; 1846 -1.0; 2031 -0.1; 2234 0.6; 2457 1.6; 2703 2.8; 2973 4.7; 3270 6.0; 3597 6.0; 3957 5.9; 4353 2.4; 4788 0.3; 5267 2.6; 5793 4.2; 6373 4.0; 7010 2.5; 7711 0.3; 8482 -1.9; 9330 -3.5; 10263 -1.6; 11289 -0.2; 12418 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Acoustic Research AR H1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 25 Hz   | 0.96 | 3.8 dB  |
| Peaking | 59 Hz   | 1.81 | 2.2 dB  |
| Peaking | 3451 Hz | 2.73 | 6.7 dB  |
| Peaking | 6304 Hz | 3.58 | 4.4 dB  |
| Peaking | 9185 Hz | 4.05 | -4.2 dB |
| Peaking | 173 Hz  | 2.84 | -1.4 dB |
| Peaking | 370 Hz  | 4.67 | -2.0 dB |
| Peaking | 673 Hz  | 5.05 | -4.2 dB |
| Peaking | 750 Hz  | 6.47 | 5.0 dB  |
| Peaking | 1812 Hz | 8.26 | -2.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Acoustic%20Research%20AR%20H1/Acoustic%20Research%20AR%20H1.png)