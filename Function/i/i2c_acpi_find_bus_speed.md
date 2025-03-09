# Function: <code>i2c_acpi_find_bus_speed</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586225792,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core.c:317",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586225792,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586332896,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:273",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586332896,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586797648,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:273",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797648,
      "name": "i2c_acpi_find_bus_speed.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
    },
    {
      "addr": 18446744071586797888,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587070736,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:273",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070736,
      "name": "i2c_acpi_find_bus_speed.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446744071587070960,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587230528,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:296",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587230528,
      "name": "i2c_acpi_find_bus_speed.part.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
    },
    {
      "addr": 18446744071587230768,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587497568,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:318",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587497344,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071587500289,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587497568,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587700784,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:335",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587700544,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071587703393,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587700784,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588569136,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:335",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588568896,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071588572143,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588569136,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588593520,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:335",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588593280,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071591579035,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588593520,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588477648,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:331",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588477408,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071591521860,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071588477648,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589146016,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:363",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145776,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071592631102,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071589146016,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:368",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594514586,
      "name": "i2c_acpi_find_bus_speed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071590596288,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592255488,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:388",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592255488,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592680784,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:388",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592680784,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593426224,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:388",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_adjust_bus_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593426224,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500860856,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:335",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500860856,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446603336500861136,
      "name": "i2c_acpi_find_bus_speed",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_find_bus_speed",
      "external": false,
      "loc": "include/linux/i2c.h:993",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_find_bus_speed",
      "external": false,
      "loc": "include/linux/i2c.h:993",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "i2c_acpi_find_bus_speed",
      "external": false,
      "loc": "include/linux/i2c.h:993",
      "file": "drivers/i2c/busses/i2c-designware-platdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587652032,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:335",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587651792,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071587654641,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587652032,
      "name": "i2c_acpi_find_bus_speed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u32 i2c_acpi_find_bus_speed(struct device * dev)
```

```json
{
  "name": "i2c_acpi_find_bus_speed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587763312,
      "name": "i2c_acpi_find_bus_speed",
      "external": true,
      "loc": "drivers/i2c/i2c-core-acpi.c:335",
      "file": "drivers/i2c/i2c-core-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587763072,
      "name": "i2c_acpi_find_bus_speed.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071587765921,
      "name": "i2c_acpi_find_bus_speed.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071587763312,
      "name": "i2c_acpi_find_bus_speed",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
u32 i2c_acpi_find_bus_speed(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
