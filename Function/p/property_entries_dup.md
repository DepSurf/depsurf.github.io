# Function: <code>property_entries_dup</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585033520,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/property.c:758",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_add_properties",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033520,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
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
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585456384,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/property.c:799",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_add_properties",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456384,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 703
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
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585700064,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/property.c:859",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:device_add_properties",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585700064,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 779
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
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585834416,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:380",
      "file": "drivers/base/swnode.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834416,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 826
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586072222,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586071296,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071586072096,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586219630,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218704,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071586219504,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586984009,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:296",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586983056,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071586983344,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587069577,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:296",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068576,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071587068864,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586955658,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:310",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952832,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071586953088,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587521658,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:312",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587519440,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
    },
    {
      "addr": 18446744071587519696,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588849122,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:312",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588847408,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071588847712,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590353442,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:312",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590351904,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071590352224,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590674386,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:312",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590672864,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071590673168,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591035746,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:312",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591034224,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071591034528,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499029656,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499028664,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    },
    {
      "addr": 18446603336499029488,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231590132,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231589248,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 736
    },
    {
      "addr": 3231589984,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292197284,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292196016,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
    },
    {
      "addr": 13835058055292197104,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276395440,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276394614,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    },
    {
      "addr": 18446743936276395292,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585979838,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585978912,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071585979712,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585829102,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585828176,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071585828976,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586169646,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168720,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071586169520,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```

```json
{
  "name": "property_entries_dup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586279118,
      "name": "property_entries_dup",
      "external": true,
      "loc": "drivers/base/swnode.c:419",
      "file": "drivers/base/swnode.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": [
        "drivers/base/swnode.c:fwnode_create_software_node",
        "drivers/spi/spi.c:spi_register_board_info",
        "drivers/i2c/i2c-boardinfo.c:i2c_register_board_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586278192,
      "name": "property_entries_dup.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
    },
    {
      "addr": 18446744071586278992,
      "name": "property_entries_dup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct property_entry * property_entries_dup(const struct property_entry * properties)
```
</details>
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
