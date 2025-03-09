# Struct: <code>twl4030_platform_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct twl4030_platform_data {
    struct twl4030_clock_init_data * clock;
    struct twl4030_bci_platform_data * bci;
    struct twl4030_gpio_platform_data * gpio;
    struct twl4030_madc_platform_data * madc;
    struct twl4030_keypad_data * keypad;
    struct twl4030_usb_data * usb;
    struct twl4030_power_data * power;
    struct twl4030_audio_data * audio;
    struct regulator_init_data * vdac;
    struct regulator_init_data * vaux1;
    struct regulator_init_data * vaux2;
    struct regulator_init_data * vaux3;
    struct regulator_init_data * vdd1;
    struct regulator_init_data * vdd2;
    struct regulator_init_data * vdd3;
    struct regulator_init_data * vpll1;
    struct regulator_init_data * vpll2;
    struct regulator_init_data * vmmc1;
    struct regulator_init_data * vmmc2;
    struct regulator_init_data * vsim;
    struct regulator_init_data * vaux4;
    struct regulator_init_data * vio;
    struct regulator_init_data * vintana1;
    struct regulator_init_data * vintana2;
    struct regulator_init_data * vintdig;
    struct regulator_init_data * vmmc;
    struct regulator_init_data * vpp;
    struct regulator_init_data * vusim;
    struct regulator_init_data * vana;
    struct regulator_init_data * vcxio;
    struct regulator_init_data * vusb;
    struct regulator_init_data * clk32kg;
    struct regulator_init_data * v1v8;
    struct regulator_init_data * v2v1;
    struct regulator_init_data * ldo1;
    struct regulator_init_data * ldo2;
    struct regulator_init_data * ldo3;
    struct regulator_init_data * ldo4;
    struct regulator_init_data * ldo5;
    struct regulator_init_data * ldo6;
    struct regulator_init_data * ldo7;
    struct regulator_init_data * ldoln;
    struct regulator_init_data * ldousb;
    struct regulator_init_data * smps3;
    struct regulator_init_data * smps4;
    struct regulator_init_data * vio6025;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
