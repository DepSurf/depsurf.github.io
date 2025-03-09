# Function: <code>acpi_dev_get_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_get_property(struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583605772,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:394",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605772,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583928797,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:394",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583928797,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069992,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:447",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069992,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584138469,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:463",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584133568,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584411874,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:468",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584406608,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584635261,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:468",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630528,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584734894,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:524",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584729216,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584936876,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931568,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585072684,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067376,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585777866,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772464,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585896292,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:531",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_check_resources",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890800,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585773349,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:531",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767824,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586256325,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:531",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250896,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587497441,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:537",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587490784,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588769650,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:696",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588760064,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589058674,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:696",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589048864,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589364034,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:700",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/acpi/acpi_apd.c:fch_misc_setup",
        "drivers/tty/serdev/core.c:acpi_serdev_add_device",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties",
        "drivers/spi/spi.c:acpi_spi_parse_apple_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589354064,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497477128,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/perf/xgene_pmu.c:acpi_pmu_dev_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497470096,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585002172,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584996864,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584917756,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912448,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585024268,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585018960,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```

```json
{
  "name": "acpi_dev_get_property",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585130444,
      "name": "acpi_dev_get_property",
      "external": true,
      "loc": "drivers/acpi/property.c:528",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_init_properties"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpio_count",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device",
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125136,
      "name": "acpi_dev_get_property",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_device * adev</code> ➡️ <code>const struct acpi_device * adev</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_dev_get_property(const struct acpi_device * adev, const char * name, acpi_object_type type, const union acpi_object * * obj)
```
</details>
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
