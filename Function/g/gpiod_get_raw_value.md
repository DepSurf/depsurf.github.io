# Function: <code>gpiod_get_raw_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194144,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1303",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core.c:get_scl_gpio_value",
        "drivers/i2c/i2c-core.c:get_sda_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194144,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583495920,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2262",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core.c:get_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495920,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583636064,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2452",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core.c:get_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583636064,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583674992,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2456",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674992,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583932688,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2669",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/i2c/i2c-core-base.c:get_sda_gpio_value",
        "drivers/i2c/i2c-core-base.c:get_scl_gpio_value"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583932688,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584124864,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2845",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124864,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584208480,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2964",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584208480,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3052",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411771,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584397744,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532800,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532800,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585221218,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585204736,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2643",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387851,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585361392,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2620",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591330161,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071585244944,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2660",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353066,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    },
    {
      "addr": 18446744071585700640,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2781",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594214690,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071586867760,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2851",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205466,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588015104,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2892",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730545,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588290144,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3085",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597638916,
      "name": "gpiod_get_raw_value.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588583840,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496708760,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496708760,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230008524,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/omap-serial.c:serial_omap_start_tx",
        "drivers/tty/serial/omap-serial.c:serial_omap_stop_tx",
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230008524,
      "name": "gpiod_get_raw_value",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290805616,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290805616,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275476958,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275476958,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489728,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489728,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584427856,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584427856,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484464,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484464,
      "name": "gpiod_get_raw_value",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int gpiod_get_raw_value(const struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_raw_value",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584590640,
      "name": "gpiod_get_raw_value",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3410",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mfd/ezx-pcap.c:pcap_isr_work",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590640,
      "name": "gpiod_get_raw_value",
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
