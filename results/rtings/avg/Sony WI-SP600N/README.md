# Sony WI-SP600N
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -0.5dB
GraphicEQ: 21 -8.7; 23 -9.0; 25 -9.3; 28 -9.5; 31 -9.6; 34 -9.7; 37 -9.7; 41 -9.7; 45 -9.6; 49 -9.4; 54 -9.3; 60 -9.3; 66 -9.3; 72 -9.2; 79 -9.1; 87 -9.0; 96 -9.0; 106 -9.0; 116 -9.0; 128 -9.0; 141 -8.9; 155 -8.7; 170 -8.5; 187 -8.3; 206 -8.1; 227 -7.7; 249 -7.3; 274 -6.7; 302 -6.1; 332 -5.6; 365 -5.0; 402 -4.6; 442 -4.1; 486 -3.6; 535 -3.1; 588 -2.5; 647 -1.8; 712 -1.2; 783 -0.6; 861 -0.3; 947 -0.1; 1042 -0.1; 1146 -1.1; 1261 -2.2; 1387 -2.8; 1526 -2.9; 1678 -2.9; 1846 -2.9; 2031 -2.7; 2234 -1.9; 2457 -1.0; 2703 -0.9; 2973 -1.6; 3270 -2.4; 3597 -2.6; 3957 -1.7; 4353 -0.8; 4788 -0.1; 5267 0.2; 5793 -1.5; 6373 -7.5; 7010 -2.2; 7711 0.3; 8482 0.0; 9330 -0.2; 10263 -7.3; 11289 -11.2; 12418 -7.0; 13660 -0.7; 15026 0.0; 16529 -4.7; 18182 -10.7; 20000 -6.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony WI-SP600N GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-5**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony WI-SP600N ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-0.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **--1.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 35 Hz    | 0.2  | -9.3 dB  |
| Peaking | 221 Hz   | 0.68 | -4.3 dB  |
| Peaking | 2451 Hz  | 0.62 | -2.0 dB  |
| Peaking | 11212 Hz | 4.52 | -11.8 dB |
| Peaking | 18664 Hz | 2.05 | -12.0 dB |
| Peaking | 909 Hz   | 4.1  | 1.8 dB   |
| Peaking | 5345 Hz  | 3.97 | 2.4 dB   |
| Peaking | 6390 Hz  | 6.15 | -8.1 dB  |
| Peaking | 7877 Hz  | 3.03 | 2.7 dB   |
| Peaking | 14797 Hz | 5.83 | 3.0 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Sony%20WI-SP600N/Sony%20WI-SP600N.png)