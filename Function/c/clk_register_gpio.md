# Function: <code>clk_register_gpio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct clk * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098944,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:97",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate",
        "drivers/clk/clk-gpio.c:clk_register_gpio_mux"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098944,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586511184,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:97",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586511184,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584317888,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:97",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584317888,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, unsigned int gpio, bool active_low, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584396384,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:97",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584396384,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 595
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584803408,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:95",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584803408,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585033392,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:95",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033392,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585140960,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:92",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585140960,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585348176,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348176,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585486720,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486720,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207888,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586207888,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586327424,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586327424,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586201120,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201120,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586704416,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586704416,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587978000,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978000,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589342144,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589342144,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589640720,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589640720,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589951072,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:139",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:gpio_clk_driver_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589951072,
      "name": "clk_register_gpio.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497788312,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497788312,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230606764,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230606764,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275923908,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275923908,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585249248,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585249248,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585201424,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201424,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437120,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437120,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
```

```json
{
  "name": "clk_register_gpio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585545040,
      "name": "clk_register_gpio",
      "external": false,
      "loc": "drivers/clk/clk-gpio.c:121",
      "file": "drivers/clk/clk-gpio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_mux",
        "drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585545040,
      "name": "clk_register_gpio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct clk *</code> ➡️ <code>struct clk_hw *</code>
</li>
</ul>
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
<code>dev, name, parent_names, num_parents, gpio, active_low, flags, clk_gpio_ops</code> ➡️ <code>dev, name, parent_names, num_parents, gpiod, flags, clk_gpio_ops</code>
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
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
struct clk_hw * clk_register_gpio(struct device * dev, const char * name, const const char * * parent_names, u8 num_parents, struct gpio_desc * gpiod, long unsigned int flags, const struct clk_ops * clk_gpio_ops)
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
