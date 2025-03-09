# Function: <code>gpiod_free_commit</code>

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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924544,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2246",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924544,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584118512,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2360",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584118512,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202608,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2388",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_hog",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202608,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 238
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584391760,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2452",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584391760,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584527456,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584527456,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585198688,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:3151",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198688,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585357120,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1955",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585357120,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585239296,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1932",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239296,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 333
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:1954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc",
        "drivers/gpio/gpiolib.c:gpiochip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694656,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071592351404,
      "name": "gpiod_free_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2015",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586857200,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071594212574,
      "name": "gpiod_free_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2085",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002672,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071596205292,
      "name": "gpiod_free_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2122",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278448,
      "name": "gpiod_free_commit.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    },
    {
      "addr": 18446744071596730305,
      "name": "gpiod_free_commit.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2305",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588570192,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
    },
    {
      "addr": 18446744071597638662,
      "name": "gpiod_free_commit.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496713856,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496713856,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230002544,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230002544,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290797312,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290797312,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275471586,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_free_hogs",
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275471586,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484384,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484384,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422512,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422512,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479120,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479120,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
bool gpiod_free_commit(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free_commit",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584585232,
      "name": "gpiod_free_commit",
      "external": false,
      "loc": "drivers/gpio/gpiolib.c:2784",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_request_own_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584585232,
      "name": "gpiod_free_commit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool gpiod_free_commit(struct gpio_desc * desc)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
bool gpiod_free_commit(struct gpio_desc * desc)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
bool gpiod_free_commit(struct gpio_desc * desc)
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
