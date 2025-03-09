# Function: <code>gpiod_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583198592,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1002",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583198592,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583502672,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1954",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502672,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583642304,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642304,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583681488,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2142",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681488,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583936976,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2279",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583936976,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584125984,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2393",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125984,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584210352,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2422",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210352,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584399072,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2486",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584399072,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584534608,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534608,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585199590,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3194",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:lineevent_create",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib.c:linehandle_release"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585210480,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585357894,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2003",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585362080,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585240998,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1980",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245632,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585696710,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2002",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585701376,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586861974,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2063",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpiod_get_index"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_release",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586868864,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588009462,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2133",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_release",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016992,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588282998,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2168",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_release",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588291552,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588576230,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2347",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request",
        "drivers/gpio/gpiolib.c:gpiod_find_and_request"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-cdev.c:lineevent_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linehandle_create",
        "drivers/gpio/gpiolib-cdev.c:linehandle_release",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588585248,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496719752,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496719752,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230010784,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230010784,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290809616,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290809616,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275478720,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275478720,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584491536,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584491536,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584429664,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584429664,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584486272,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486272,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void gpiod_free(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584592496,
      "name": "gpiod_free",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2818",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_put_array",
        "drivers/gpio/gpiolib.c:fwnode_get_named_gpiod",
        "drivers/gpio/gpiolib.c:gpiod_get_index",
        "drivers/gpio/gpiolib.c:gpio_ioctl",
        "drivers/gpio/gpiolib.c:lineevent_release",
        "drivers/gpio/gpiolib.c:linehandle_create",
        "drivers/gpio/gpiolib.c:linehandle_release",
        "drivers/gpio/gpiolib-legacy.c:gpio_free_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_array",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister",
        "drivers/gpio/gpiolib-sysfs.c:unexport_store",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592496,
      "name": "gpiod_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
