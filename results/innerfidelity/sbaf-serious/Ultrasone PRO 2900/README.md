# Ultrasone PRO 2900

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 2.9; 25 1.8; 28 0.4; 31 -0.8; 34 -1.7; 37 -2.5; 41 -3.1; 45 -3.6; 49 -4.0; 54 -4.4; 60 -4.5; 66 -4.2; 72 -3.9; 79 -4.0; 87 -3.9; 96 -3.8; 106 -3.5; 116 -3.1; 128 -2.8; 141 -2.5; 155 -2.2; 170 -1.6; 187 -1.2; 206 -1.6; 227 -2.6; 249 -2.4; 274 -1.5; 302 -0.9; 332 -0.4; 365 0.1; 402 0.4; 442 0.7; 486 0.9; 535 1.2; 588 2.6; 647 2.4; 712 1.8; 783 1.7; 861 1.0; 947 0.4; 1042 -0.2; 1146 -0.5; 1261 -0.9; 1387 -0.9; 1526 -1.3; 1678 -1.7; 1846 -1.5; 2031 -1.5; 2234 5.6; 2457 0.3; 2703 -1.8; 2973 -2.8; 3270 -4.4; 3597 -6.1; 3957 -6.0; 4353 -2.7; 4788 5.6; 5267 2.7; 5793 -2.8; 6373 -6.3; 7010 -2.2; 7711 0.3; 8482 0.0; 9330 0.0; 10263 0.0; 11289 0.0; 12418 0.0; 13660 -3.1; 15026 -8.6; 16529 -7.3; 18182 -2.7; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Ultrasone PRO 2900 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -4.7dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 20 Hz    | 1.37 | 6.3 dB  |
| Peaking | 61 Hz    | 0.52 | -4.8 dB |
| Peaking | 3627 Hz  | 4.52 | -7.0 dB |
| Peaking | 15816 Hz | 2.48 | -9.8 dB |
| Peaking | 24000 Hz | 2.01 | -3.3 dB |
| Peaking | 645 Hz   | 2.09 | 2.9 dB  |
| Peaking | 2112 Hz  | 1.59 | -3.9 dB |
| Peaking | 2233 Hz  | 7.1  | 10.1 dB |
| Peaking | 4930 Hz  | 8.45 | 8.5 dB  |
| Peaking | 6369 Hz  | 7.07 | -6.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Ultrasone%20PRO%202900/Ultrasone%20PRO%202900.png)