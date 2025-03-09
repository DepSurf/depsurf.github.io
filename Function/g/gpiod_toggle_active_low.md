# Function: <code>gpiod_toggle_active_low</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523728,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523728,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3643",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585220851,
      "name": "gpiod_toggle_active_low.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585204336,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2469",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387484,
      "name": "gpiod_toggle_active_low.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585360992,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2446",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591329794,
      "name": "gpiod_toggle_active_low.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585244544,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2475",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592352548,
      "name": "gpiod_toggle_active_low.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585700128,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2593",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214289,
      "name": "gpiod_toggle_active_low.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071586867296,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588014304,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2663",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588014304,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289152,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2704",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289152,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588582848,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2897",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588582848,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496707944,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496707944,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230003252,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230003252,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290790640,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290790640,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275467174,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275467174,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584480656,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480656,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418784,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418784,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584475392,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475392,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_toggle_active_low",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581520,
      "name": "gpiod_toggle_active_low",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3235",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581520,
      "name": "gpiod_toggle_active_low",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc * desc)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
