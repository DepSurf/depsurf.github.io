# Function: <code>gpiod_unexport</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203376,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:676",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:__gpiod_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203376,
      "name": "gpiod_unexport",
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583511344,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:678",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:__gpiod_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583511344,
      "name": "gpiod_unexport",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583651152,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:678",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:__gpiod_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651152,
      "name": "gpiod_unexport",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690592,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:687",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:__gpiod_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690592,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947424,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:687",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947424,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:702",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584142055,
      "name": "gpiod_unexport.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584140400,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584229703,
      "name": "gpiod_unexport.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584229024,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419431,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584418768,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584555783,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584555120,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585228898,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585226864,
      "name": "gpiod_unexport",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:698",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591389300,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585384960,
      "name": "gpiod_unexport",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:706",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591331740,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585269040,
      "name": "gpiod_unexport",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:695",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592355198,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585725152,
      "name": "gpiod_unexport",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:678",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594217406,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586902720,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055296,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:678",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055296,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588329648,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:688",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588329648,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588623824,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:690",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588623824,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496747632,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496747632,
      "name": "gpiod_unexport",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230036096,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230036096,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290843792,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290843792,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275500908,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275500908,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584512711,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584512048,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450839,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584450176,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584507447,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584506784,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
void gpiod_unexport(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_unexport",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_unexport",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:697",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_free_commit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613719,
      "name": "gpiod_unexport.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584613056,
      "name": "gpiod_unexport",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
