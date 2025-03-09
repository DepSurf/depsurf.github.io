# Function: <code>gpiod_get_direction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583186784,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:157",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:__gpiod_request",
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583186784,
      "name": "gpiod_get_direction",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583487328,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:179",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:__gpiod_request",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583487328,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583626288,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:182",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:__gpiod_request",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583626288,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670656,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:183",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:__gpiod_request",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670656,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583925360,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:203",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583925360,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584119232,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:211",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584119232,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584203120,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:212",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203120,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584392272,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:212",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392272,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584520640,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520640,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199664,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:215",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dbg_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199664,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585354208,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:212",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_dbg_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585354208,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585238144,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585238144,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585693456,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585693456,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586851392,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:213",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851392,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587995840,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587995840,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270528,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:233",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270528,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588562896,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:312",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_init_recovery"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588562896,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496715616,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496715616,
      "name": "gpiod_get_direction",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229996540,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996540,
      "name": "gpiod_get_direction",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290785200,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290785200,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275463910,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275463910,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584477568,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584477568,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584415696,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415696,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584472304,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472304,
      "name": "gpiod_get_direction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int gpiod_get_direction(struct gpio_desc * desc)
```

```json
{
  "name": "gpiod_get_direction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584578432,
      "name": "gpiod_get_direction",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:214",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiolib_seq_show",
        "drivers/gpio/gpiolib.c:gpiochip_lock_as_irq",
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib-sysfs.c:direction_show",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578432,
      "name": "gpiod_get_direction",
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
