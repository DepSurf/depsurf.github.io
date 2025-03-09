# Function: <code>gpio_set_open_drain_value_commit</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931024,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2757",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931024,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2933",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123280,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584136685,
      "name": "gpio_set_open_drain_value_commit.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3060",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207200,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071584222403,
      "name": "gpio_set_open_drain_value_commit.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3148",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584395872,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    },
    {
      "addr": 18446744071584411597,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584531520,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584548213,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3914",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202624,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071585220158,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2739",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358528,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    },
    {
      "addr": 18446744071591386701,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2716",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241584,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071591328880,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2756",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697296,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071592351738,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2877",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586864112,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
    },
    {
      "addr": 18446744071594213495,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010416,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2947",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588010416,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285408,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2988",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285408,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588578320,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3181",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588578320,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496717952,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496717952,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230006904,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230006904,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290803312,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290803312,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275475548,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275475548,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584488448,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584505141,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584426576,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584443269,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584483184,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071584499877,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_drain_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_drain_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3506",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_value_nocheck",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_complex"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589280,
      "name": "gpio_set_open_drain_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071584606149,
      "name": "gpio_set_open_drain_value_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void gpio_set_open_drain_value_commit(struct gpio_desc * desc, bool value)
```
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
