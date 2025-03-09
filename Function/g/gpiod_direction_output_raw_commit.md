# Function: <code>gpiod_direction_output_raw_commit</code>

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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583930080,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2418",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583930080,
      "name": "gpiod_direction_output_raw_commit",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2532",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584124032,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 315
    },
    {
      "addr": 18446744071584136825,
      "name": "gpiod_direction_output_raw_commit.cold.49",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2589",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584209232,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071584222543,
      "name": "gpiod_direction_output_raw_commit.cold.47",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2677",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584397920,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071584411809,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533568,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071584548349,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3412",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201120,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
    },
    {
      "addr": 18446744071585220030,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2255",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356704,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 415
    },
    {
      "addr": 18446744071591386478,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2232",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585243120,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
    },
    {
      "addr": 18446744071591329028,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2261",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585698800,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071592351886,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2322",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865216,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071594213643,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588012160,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2392",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588012160,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588286768,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2433",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286768,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588579936,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2627",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588579936,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496712224,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496712224,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230009460,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230009460,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290806816,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290806816,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275477624,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275477624,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490496,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071584505277,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584428624,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071584443405,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485232,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071584500013,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
```

```json
{
  "name": "gpiod_direction_output_raw_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_direction_output_raw_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3009",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output",
        "drivers/gpio/gpiolib.c:gpiod_direction_output_raw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584591408,
      "name": "gpiod_direction_output_raw_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
    },
    {
      "addr": 18446744071584606285,
      "name": "gpiod_direction_output_raw_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int gpiod_direction_output_raw_commit(struct gpio_desc * desc, int value)
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
