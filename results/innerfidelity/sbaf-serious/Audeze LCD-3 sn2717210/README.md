# Audeze LCD-3 sn2717210
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 5.9; 28 4.7; 31 3.4; 34 2.6; 37 2.3; 41 2.0; 45 2.1; 49 2.2; 54 2.1; 60 2.1; 66 2.0; 72 1.8; 79 1.5; 87 1.2; 96 0.7; 106 0.5; 116 0.4; 128 0.1; 141 -0.2; 155 -0.4; 170 -0.6; 187 -0.7; 206 -0.8; 227 -0.8; 249 -0.9; 274 -0.9; 302 -0.9; 332 -1.0; 365 -0.9; 402 -1.0; 442 -0.9; 486 -0.9; 535 -0.6; 588 0.3; 647 0.8; 712 0.0; 783 -0.4; 861 -0.5; 947 -0.2; 1042 0.2; 1146 0.5; 1261 0.9; 1387 -0.2; 1526 -1.6; 1678 -1.6; 1846 -0.5; 2031 0.4; 2234 0.4; 2457 1.8; 2703 3.0; 2973 3.6; 3270 4.0; 3597 5.5; 3957 6.0; 4353 5.3; 4788 3.3; 5267 2.6; 5793 -0.9; 6373 2.7; 7010 2.5; 7711 0.3; 8482 0.0; 9330 0.0; 10263 0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 -0.3; 18182 -2.4; 20000 -4.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audeze LCD-3 sn2717210 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audeze LCD-3 sn2717210 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc       |     Q | Gain    |
|:--------|:---------|:------|:--------|
| Peaking | 22 Hz    |  1.4  | 6.3 dB  |
| Peaking | 63 Hz    |  2.09 | 1.7 dB  |
| Peaking | 1636 Hz  |  4.9  | -2.3 dB |
| Peaking | 2808 Hz  |  3.83 | 1.5 dB  |
| Peaking | 3945 Hz  |  2.12 | 6.0 dB  |
| Peaking | 294 Hz   |  1.02 | -1.1 dB |
| Peaking | 1273 Hz  |  5.07 | 1.7 dB  |
| Peaking | 1419 Hz  |  4.08 | -0.9 dB |
| Peaking | 6717 Hz  | 13.75 | 3.6 dB  |
| Peaking | 19640 Hz |  1.75 | -4.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audeze%20LCD-3%20sn2717210/Audeze%20LCD-3%20sn2717210.png)