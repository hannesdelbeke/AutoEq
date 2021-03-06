# Popclik EVOLO

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.2dB
GraphicEQ: 21 -10.1; 23 -10.2; 25 -10.3; 28 -10.5; 31 -10.6; 34 -10.7; 37 -10.8; 41 -10.8; 45 -10.8; 49 -10.8; 54 -10.8; 60 -10.9; 66 -10.9; 72 -10.9; 79 -11.0; 87 -11.0; 96 -11.0; 106 -10.8; 116 -10.5; 128 -10.4; 141 -10.1; 155 -9.8; 170 -9.3; 187 -8.9; 206 -8.4; 227 -7.8; 249 -7.3; 274 -6.6; 302 -5.9; 332 -5.2; 365 -4.6; 402 -3.9; 442 -3.2; 486 -2.6; 535 -2.0; 588 -1.1; 647 -0.7; 712 -0.3; 783 0.2; 861 0.2; 947 0.3; 1042 -0.0; 1146 -0.3; 1261 -0.7; 1387 -1.4; 1526 -2.4; 1678 -3.5; 1846 -4.0; 2031 -4.2; 2234 -4.6; 2457 -4.5; 2703 -4.2; 2973 -2.3; 3270 0.2; 3597 1.9; 3957 1.6; 4353 -0.5; 4788 -2.2; 5267 -4.0; 5793 -7.8; 6373 -6.9; 7010 -1.8; 7711 0.3; 8482 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-2.2dB` and instead set Global volume in the UI for both channels to **-22**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Popclik EVOLO ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -2.5dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 37 Hz   | 0.24 | -10.5 dB |
| Peaking | 177 Hz  | 0.68 | -4.6 dB  |
| Peaking | 2307 Hz | 1.73 | -5.2 dB  |
| Peaking | 3655 Hz | 4.22 | 4.2 dB   |
| Peaking | 5951 Hz | 4.88 | -9.1 dB  |
| Peaking | 370 Hz  | 1.78 | -0.8 dB  |
| Peaking | 851 Hz  | 1.29 | 1.5 dB   |
| Peaking | 1653 Hz | 4.84 | -1.5 dB  |
| Peaking | 7596 Hz | 7.32 | 1.7 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Popclik%20EVOLO/Popclik%20EVOLO.png)