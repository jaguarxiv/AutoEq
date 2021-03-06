# Sennheiser PX 100
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 3.4; 25 2.8; 28 2.1; 31 1.6; 34 1.1; 37 0.7; 41 0.2; 45 -0.2; 49 -0.5; 54 -0.8; 60 -1.2; 66 -1.5; 72 -1.9; 79 -2.1; 87 -2.5; 96 -2.9; 106 -3.1; 116 -3.2; 128 -3.4; 141 -3.4; 155 -3.5; 170 -3.5; 187 -3.2; 206 -2.9; 227 -2.6; 249 -2.4; 274 -2.2; 302 -2.0; 332 -1.7; 365 -1.3; 402 -1.1; 442 -0.6; 486 -0.4; 535 -0.2; 588 0.1; 647 0.3; 712 0.3; 783 0.4; 861 0.2; 947 0.1; 1042 -0.1; 1146 -0.3; 1261 -0.8; 1387 -1.7; 1526 -2.7; 1678 -3.5; 1846 -3.5; 2031 -2.2; 2234 -0.4; 2457 1.9; 2703 4.9; 2973 6.0; 3270 6.0; 3597 5.1; 3957 -2.1; 4353 -5.3; 4788 0.4; 5267 5.5; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser PX 100 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser PX 100 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.6dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 21 Hz    | 1.29 | 4.3 dB   |
| Peaking | 137 Hz   | 0.71 | -3.7 dB  |
| Peaking | 3310 Hz  | 1.99 | 15.6 dB  |
| Peaking | 4321 Hz  | 1.22 | -25.0 dB |
| Peaking | 5365 Hz  | 1.37 | 19.5 dB  |
| Peaking | 888 Hz   | 1.28 | 1.5 dB   |
| Peaking | 1769 Hz  | 2.86 | -3.0 dB  |
| Peaking | 2659 Hz  | 7.48 | 2.6 dB   |
| Peaking | 7950 Hz  | 5.4  | -1.5 dB  |
| Peaking | 11255 Hz | 0.46 | 0.4 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20PX%20100/Sennheiser%20PX%20100.png)