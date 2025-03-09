# Function: <code>gpio_set_open_source_value_commit</code>

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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931344,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
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
      "addr": 18446744071583931344,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2960",
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
      "addr": 18446744071584123536,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071584136755,
      "name": "gpio_set_open_source_value_commit.cold.48",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3087",
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
      "addr": 18446744071584207456,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
    },
    {
      "addr": 18446744071584222473,
      "name": "gpio_set_open_source_value_commit.cold.46",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3175",
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
      "addr": 18446744071584396112,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
    },
    {
      "addr": 18446744071584411665,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446744071584531760,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071584548281,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3939",
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
      "addr": 18446744071585202864,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071585220226,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2764",
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
      "addr": 18446744071585358736,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 18446744071591386775,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2741",
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
      "addr": 18446744071585241792,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071591328954,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2781",
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
      "addr": 18446744071585697504,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    },
    {
      "addr": 18446744071592351812,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2902",
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
      "addr": 18446744071586864352,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    },
    {
      "addr": 18446744071594213569,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588010768,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2972",
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
      "addr": 18446744071588010768,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285760,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3013",
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
      "addr": 18446744071588285760,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588578640,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3206",
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
      "addr": 18446744071588578640,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496718320,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446603336496718320,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230007244,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 3230007244,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290803760,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 13835058055290803760,
      "name": "gpio_set_open_source_value_commit",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275475838,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446743936275475838,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446744071584488688,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071584505209,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446744071584426816,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071584443337,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446744071584483424,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    },
    {
      "addr": 18446744071584499945,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
```

```json
{
  "name": "gpio_set_open_source_value_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpio_set_open_source_value_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3531",
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
      "addr": 18446744071584589536,
      "name": "gpio_set_open_source_value_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071584606217,
      "name": "gpio_set_open_source_value_commit.cold",
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
void gpio_set_open_source_value_commit(struct gpio_desc * desc, bool value)
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
