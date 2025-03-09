# Function: <code>gpiod_get_array_value_complex</code>

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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583939840,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2613",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583939840,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 813
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584128912,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2771",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584128912,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584213120,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2851",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584213120,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1234
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2939",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412006,
      "name": "gpiod_get_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071584401984,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1204
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537648,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537648,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585210560,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3705",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210560,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585362256,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2531",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362256,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1262
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245792,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2508",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245792,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1295
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2537",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592353744,
      "name": "gpiod_get_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071585701536,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1486
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2658",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594215881,
      "name": "gpiod_get_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071586869104,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1592
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2728",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205550,
      "name": "gpiod_get_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071588017248,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1718
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2769",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730608,
      "name": "gpiod_get_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071588291792,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1569
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2962",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linereq_get_values",
        "drivers/gpio/gpiolib-cdev.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597638979,
      "name": "gpiod_get_array_value_complex.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071588585664,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1524
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496723512,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496723512,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1224
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230014000,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230014000,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1288
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290813680,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290813680,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1444
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275481268,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275481268,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584494576,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494576,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432704,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432704,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584489312,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584489312,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1218
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, struct gpio_array * array_info, long unsigned int * value_bitmap)
```

```json
{
  "name": "gpiod_get_array_value_complex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584595536,
      "name": "gpiod_get_array_value_complex",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3297",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value_cansleep",
        "drivers/gpio/gpiolib.c:gpiod_get_array_value",
        "drivers/gpio/gpiolib.c:gpiod_get_raw_array_value",
        "drivers/gpio/gpiolib.c:linehandle_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584595536,
      "name": "gpiod_get_array_value_complex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1243
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
int gpiod_get_array_value_complex(bool raw, bool can_sleep, unsigned int array_size, struct gpio_desc * * desc_array, int * value_array)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
