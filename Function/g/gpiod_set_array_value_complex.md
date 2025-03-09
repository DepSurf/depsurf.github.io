# Function: <code>gpiod_set_array_value_complex</code>

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
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506544,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2398",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506544,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583646096,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2588",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583646096,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583684320,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2585",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583684320,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 778
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
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940848,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2838",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940848,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 840
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584130112,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3014",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130112,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1010
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584214560,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584214560,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1178
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3229",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412063,
      "name": "gpiod_set_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071584403392,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1173
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539072,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539072,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212000,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3992",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212000,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1203
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585363712,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2817",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363712,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1188
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585247280,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2794",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585247280,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1318
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2834",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353844,
      "name": "gpiod_set_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    },
    {
      "addr": 18446744071585703216,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1333
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2955",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594215994,
      "name": "gpiod_set_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071586871072,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1468
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3025",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205637,
      "name": "gpiod_set_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071588019424,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1537
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3066",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730695,
      "name": "gpiod_set_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    },
    {
      "addr": 18446744071588293824,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1535
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3259",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_values",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597639079,
      "name": "gpiod_set_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    },
    {
      "addr": 18446744071588587664,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1466
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496725120,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496725120,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1120
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230015584,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230015584,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1252
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290815392,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290815392,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1384
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275482524,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275482524,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584496000,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584496000,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584434128,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584434128,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584490736,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584490736,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1184
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
int gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_set_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596976,
      "name": "gpiod_set_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3583",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_set_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_set_array_value",
        "drivers/gpio/gpiolib.c:gpiod_set_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596976,
      "name": "gpiod_set_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1209
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
void gpiod_set_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
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
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_array * array_info</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int * value_bitmap</code>
</li>
<li>
<b>Param removed. </b>
<code>int * value_array</code>
</li>
</ul>
</details>
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
