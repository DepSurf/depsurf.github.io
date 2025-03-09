# Function: <code>acpi_device_add_finalize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566243,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1407",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566243,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888198,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1427",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888198,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584027312,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1457",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_add_single_object",
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027312,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584083724,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1486",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584086704,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584354059,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1585",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584357472,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584574932,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1588",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578352,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584672199,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1601",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584675696,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584872241,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584875488,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585008113,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585011360,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585709259,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1609",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585710992,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585831758,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1676",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585834000,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585710964,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1690",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585713296,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586192360,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1772",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586194624,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587428460,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1815",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587430928,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588686067,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1799",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588689296,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588973832,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1802",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977216,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589271367,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1814",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589274848,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497419016,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497422264,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584951793,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584954736,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584860593,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584863536,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584959697,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962944,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```

```json
{
  "name": "acpi_device_add_finalize",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585065873,
      "name": "acpi_device_add_finalize",
      "external": true,
      "loc": "drivers/acpi/scan.c:1600",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_add_single_object"
      ],
      "caller_func": [
        "drivers/acpi/power.c:acpi_add_power_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585069120,
      "name": "acpi_device_add_finalize",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void acpi_device_add_finalize(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_device_add_finalize(struct acpi_device * device)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_device_add_finalize(struct acpi_device * device)
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
