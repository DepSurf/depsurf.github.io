# Function: <code>bgpio_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:599",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594218058,
      "name": "bgpio_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071586913232,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588068096,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:599",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588068096,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 954
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588342640,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:599",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588342640,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 950
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:598",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597639844,
      "name": "bgpio_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071588636896,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1096
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496761280,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:582",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496761280,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230038844,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:582",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe",
        "drivers/gpio/gpio-mxc.c:mxc_gpio_probe",
        "drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230038844,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 912
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290849776,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:582",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290849776,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275504218,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:582",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275504218,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 772
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```

```json
{
  "name": "bgpio_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bgpio_init",
      "external": true,
      "loc": "drivers/gpio/gpio-mmio.c:582",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524975,
      "name": "bgpio_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071584523008,
      "name": "bgpio_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1017
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➕</summary>

```c
int bgpio_init(struct gpio_chip * gc, struct device * dev, long unsigned int sz, void * dat, void * set, void * clr, void * dirout, void * dirin, long unsigned int flags)
```
</details>
</li>
</ul>
