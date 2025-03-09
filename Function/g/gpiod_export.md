# Function: <code>gpiod_export</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583203696,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:547",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203696,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 723
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583511664,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:547",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583511664,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583651472,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:547",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651472,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583690928,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:556",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690928,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583947760,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:556",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947760,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584140688,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:571",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140688,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584228032,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584228032,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584417744,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584417744,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 754
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584554112,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584554112,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585227520,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585227520,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385616,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:567",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385616,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585269696,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:575",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585269696,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585725840,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:564",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725840,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586901552,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:547",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586901552,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588054016,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:547",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054016,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328368,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:557",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328368,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 752
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622512,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:560",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622512,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 776
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496748528,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496748528,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 904
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230034788,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init",
        "arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init",
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230034788,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290844352,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290844352,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275499736,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275499736,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 730
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584511040,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584511040,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584449168,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584449168,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584505776,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584505776,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
int gpiod_export(struct gpio_desc * desc, bool direction_may_change)
```

```json
{
  "name": "gpiod_export",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584612048,
      "name": "gpiod_export",
      "external": true,
      "loc": "drivers/gpio/gpiolib-sysfs.c:566",
      "file": "drivers/gpio/gpiolib-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-legacy.c:gpio_request_one",
        "drivers/gpio/gpiolib-sysfs.c:export_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584612048,
      "name": "gpiod_export",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
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
