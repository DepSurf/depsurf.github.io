# Function: <code>acpi_dock_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583564767,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1086",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583564767,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583886682,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1106",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583886682,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584025796,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1107",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584025796,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584084794,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1098",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584080720,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584355362,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1102",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584350560,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584576242,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1103",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571584,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584673526,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1103",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668896,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584873593,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584868960,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585009465,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004832,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585706805,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1110",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init_hotplug",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585707904,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585829205,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1179",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_init_hotplug",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585830256,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585711734,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1179",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709312,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586193078,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1187",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190464,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587429248,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1217",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:is_dock_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587426528,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588686880,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1200",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:is_dock_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588683888,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588974697,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1202",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:is_dock_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588971632,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589272232,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1205",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_set_pnp_ids"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add",
        "drivers/acpi/dock.c:is_dock_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589269136,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497420148,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497415560,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584952935,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584948528,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584861735,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584857328,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584961049,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956416,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool acpi_dock_match(acpi_handle handle)
```

```json
{
  "name": "acpi_dock_match",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585067225,
      "name": "acpi_dock_match",
      "external": true,
      "loc": "drivers/acpi/scan.c:1101",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object"
      ],
      "caller_func": [
        "drivers/acpi/dock.c:acpi_dock_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062592,
      "name": "acpi_dock_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool acpi_dock_match(acpi_handle handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool acpi_dock_match(acpi_handle handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool acpi_dock_match(acpi_handle handle)
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
