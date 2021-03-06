# Sennheiser EH350
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 6.0; 79 5.9; 87 5.0; 96 4.0; 106 3.1; 116 2.7; 128 2.1; 141 2.6; 155 2.5; 170 2.1; 187 1.8; 206 1.7; 227 1.5; 249 1.4; 274 1.2; 302 1.1; 332 0.9; 365 0.8; 402 0.8; 442 0.5; 486 0.6; 535 0.9; 588 0.9; 647 1.2; 712 1.0; 783 0.2; 861 0.1; 947 -0.1; 1042 0.1; 1146 0.3; 1261 -0.5; 1387 -1.0; 1526 -1.5; 1678 -1.5; 1846 -0.0; 2031 0.6; 2234 1.2; 2457 1.5; 2703 1.3; 2973 1.3; 3270 0.9; 3597 2.7; 3957 6.0; 4353 0.7; 4788 -0.8; 5267 2.0; 5793 4.0; 6373 5.4; 7010 0.6; 7711 -2.9; 8482 -1.8; 9330 0.0; 10263 0.0; 11289 0.0; 12418 -1.5; 13660 -7.8; 15026 -8.1; 16529 -5.5; 18182 -4.4; 20000 -2.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser EH350 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser EH350 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 28 Hz    | 0.23 | 6.1 dB   |
| Peaking | 74 Hz    | 3.04 | 1.6 dB   |
| Peaking | 5638 Hz  | 0.9  | 4.8 dB   |
| Peaking | 11690 Hz | 2.04 | 11.1 dB  |
| Peaking | 13212 Hz | 0.79 | -13.2 dB |
| Peaking | 1557 Hz  | 4.87 | -2.2 dB  |
| Peaking | 4074 Hz  | 6.06 | 7.1 dB   |
| Peaking | 4524 Hz  | 6.16 | -8.1 dB  |
| Peaking | 6272 Hz  | 5.86 | 4.4 dB   |
| Peaking | 7612 Hz  | 6.63 | -3.9 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20EH350/Sennheiser%20EH350.png)