# Function: <code>gpiod_set_debounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583188464,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1218",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583188464,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489776,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2186",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489776,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628736,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2376",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628736,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583672208,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2378",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672208,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583927360,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2526",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583927360,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115840,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2640",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd",
        "drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115840,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584199200,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2720",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584199200,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584388048,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2808",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584388048,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584523936,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584523936,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204944,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3576",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204944,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585361616,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2419",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585361616,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245168,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2396",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245168,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585700880,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2425",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700880,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586868304,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2543",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586868304,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588016048,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2613",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016048,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588290576,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2654",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588290576,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588584496,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2848",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:edge_detector_setup",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584496,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496700872,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496700872,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229997708,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229997708,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290791008,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290791008,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275467408,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275467408,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584480864,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584480864,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584418992,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584418992,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584475600,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475600,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int gpiod_set_debounce(struct gpio_desc * desc, unsigned int debounce)
```

```json
{
  "name": "gpiod_set_debounce",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584581728,
      "name": "gpiod_set_debounce",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3155",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro",
        "drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584581728,
      "name": "gpiod_set_debounce",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
