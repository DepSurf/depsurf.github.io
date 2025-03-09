# Function: <code>clk_hw_register_gpio_mux</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586511840,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:206",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511840,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584318544,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:206",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584318544,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584397072,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:206",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397072,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804144,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:179",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804144,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:179",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034226,
      "name": "clk_hw_register_gpio_mux.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585034112,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:176",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585141753,
      "name": "clk_hw_register_gpio_mux.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585141520,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348929,
      "name": "clk_hw_register_gpio_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585348688,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487476,
      "name": "clk_hw_register_gpio_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585487232,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:187",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497788872,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497788872,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230607284,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230607284,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275924390,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275924390,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585250004,
      "name": "clk_hw_register_gpio_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585249760,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202180,
      "name": "clk_hw_register_gpio_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585201936,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437876,
      "name": "clk_hw_register_gpio_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585437632,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```

```json
{
  "name": "clk_hw_register_gpio_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clk_hw_register_gpio_mux",
      "external": true,
      "loc": "drivers/clk/clk-gpio.c:211",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545796,
      "name": "clk_hw_register_gpio_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585545552,
      "name": "clk_hw_register_gpio_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_desc * gpiod</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int gpio</code>
</li>
<li>
<b>Param removed. </b>
<code>bool active_low</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, name, parent_names, num_parents, gpio, active_low, flags</code> ➡️ <code>dev, name, parent_names, num_parents, gpiod, flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct clk_hw * clk_hw_register_gpio_mux(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags)
```
</details>
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
