# Function: <code>acpi_register_lapic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_register_lapic(int id, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579170816,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:168",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170816,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579171072,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:169",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171072,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579180640,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:171",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180640,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180096,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:173",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180096,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195568,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:173",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579195568,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:173",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207488,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579208257,
      "name": "acpi_register_lapic.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579231173,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:174",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231072,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579231874,
      "name": "acpi_register_lapic.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579244501,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:157",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244400,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579245186,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246693,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:157",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246592,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579247410,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:158",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270384,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071579271922,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:158",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277808,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071591257702,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:158",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579280592,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    },
    {
      "addr": 18446744071591201048,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:156",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323664,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071592071432,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:166",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383600,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071593837825,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460752,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:166",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460752,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473328,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:171",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473328,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504112,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:175",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504112,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579245541,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:157",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245440,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579246258,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180981,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:157",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180880,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579181698,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579246597,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:157",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246496,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579247314,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```

```json
{
  "name": "acpi_register_lapic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579252165,
      "name": "acpi_register_lapic",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:157",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_map_cpu",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_sapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_lapic",
        "arch/x86/kernel/acpi/boot.c:acpi_parse_x2apic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252064,
      "name": "acpi_register_lapic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071579252882,
      "name": "acpi_register_lapic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 acpiid</code>
</li>
<li>
<b>Param reordered. </b>
<code>id, enabled</code> ➡️ <code>id, acpiid, enabled</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_register_lapic(int id, u32 acpiid, u8 enabled)
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
