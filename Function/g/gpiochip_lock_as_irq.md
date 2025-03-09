# Function: <code>gpiochip_lock_as_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583190976,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:1618",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583190976,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489488,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2589",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489488,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583628432,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2779",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583628432,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667536,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:2776",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667536,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583922256,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3047",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583922256,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584115312,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3239",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584115312,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204256,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3432",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204256,
      "name": "gpiochip_lock_as_irq",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3521",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584411162,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584393440,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584547210,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584522896,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:4281",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219839,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585199792,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3105",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386133,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585354352,
      "name": "gpiochip_lock_as_irq",
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3082",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591328515,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071585238288,
      "name": "gpiochip_lock_as_irq",
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3141",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592351245,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071585694288,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3262",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_irq_reqres",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594212415,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    },
    {
      "addr": 18446744071586856848,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3332",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205271,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588002080,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3373",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596730284,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588277056,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int gpiochip_lock_as_irq(struct gpio_chip * gc, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3566",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597638641,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588569568,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496717376,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_request_resources",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_request_resources",
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496717376,
      "name": "gpiochip_lock_as_irq",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229996956,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres",
        "drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_request_resources",
        "drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_request_resources",
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229996956,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290789088,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290789088,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275466144,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275466144,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584504138,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584479824,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584442266,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584417952,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498874,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584474560,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int gpiochip_lock_as_irq(struct gpio_chip * chip, unsigned int offset)
```

```json
{
  "name": "gpiochip_lock_as_irq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gpiochip_lock_as_irq",
      "external": true,
      "loc": "drivers/gpio/gpiolib.c:3875",
      "file": "drivers/gpio/gpiolib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib.c:gpiochip_reqres_irq",
        "drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate",
        "drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584605146,
      "name": "gpiochip_lock_as_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    },
    {
      "addr": 18446744071584580688,
      "name": "gpiochip_lock_as_irq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip * gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip * chip</code>
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
