# Function: <code>device_get_next_child_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584420896,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:855",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420896,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584756342,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:874",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_get_named_child_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756320,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584946566,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:874",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_named_child_node",
        "drivers/base/property.c:device_get_named_child_node"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584946544,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585031280,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:961",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031280,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585455152,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:1004",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585455152,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697536,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:1090",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697536,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585827792,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:613",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585827792,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586062320,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586062320,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210208,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210208,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586975520,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:707",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586975520,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587060880,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:759",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060880,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586944688,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:759",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944688,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587509185,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:759",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587509008,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588835653,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:759",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588835488,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct fwnode_handle * device_get_next_child_node(const struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590336933,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:767",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590336752,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct fwnode_handle * device_get_next_child_node(const struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590657029,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:794",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656848,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct fwnode_handle * device_get_next_child_node(const struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591017557,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:858",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591017376,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499015768,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499015768,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231576824,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231576432,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292174744,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292174112,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276382272,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276381904,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585970416,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585970416,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585819680,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819680,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586160224,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160224,
      "name": "device_get_next_child_node",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct fwnode_handle * device_get_next_child_node(struct device * dev, struct fwnode_handle * child)
```

```json
{
  "name": "device_get_next_child_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268928,
      "name": "device_get_next_child_node",
      "external": true,
      "loc": "drivers/base/property.c:637",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/base/property.c:device_get_child_node_count",
        "drivers/base/property.c:device_get_child_node_count"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268928,
      "name": "device_get_next_child_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device * dev</code> ➡️ <code>const struct device * dev</code>
</li>
</ul>
</details>
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
