# Function: <code>gpiochip_line_is_valid</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584114341,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:389",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584114288,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584203390,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:398",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584197744,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584392543,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:398",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387072,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584523247,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584522368,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585203359,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:418",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585198448,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585359647,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:463",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_map",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356448,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585242491,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:461",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239248,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585697883,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:483",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585694608,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586866269,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:484",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586852720,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587996592,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:540",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_to_irq",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996592,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588271280,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:567",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271280,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool gpiochip_line_is_valid(const struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588563632,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:646",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_remove",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key",
        "drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563632,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496716104,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496699960,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230002260,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_dbg_show",
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996024,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290789768,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290788160,
      "name": "gpiochip_line_is_valid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275466574,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275465500,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584480175,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479296,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584418303,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417424,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584474911,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584474032,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```

```json
{
  "name": "gpiochip_line_is_valid",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581039,
      "name": "gpiochip_line_is_valid",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:401",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpiolib.c:gpiod_request_commit",
        "drivers/gpio/gpiolib.c:gpiochip_irqchip_irq_valid",
        "drivers/gpio/gpiolib.c:gpiochip_add_data_with_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580160,
      "name": "gpiochip_line_is_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool gpiochip_line_is_valid(const struct gpio_chip * gpiochip, unsigned int offset)
```
</details>
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct gpio_chip * gc</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct gpio_chip * gpiochip</code>
</li>
</ul>
</details>
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
