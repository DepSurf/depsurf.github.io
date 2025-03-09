# Function: <code>acpi_ev_install_gpe_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583641293,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:750",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641293,
      "name": "acpi_ev_install_gpe_handler.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964811,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:750",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964363,
      "name": "acpi_ev_install_gpe_handler.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584106400,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:750",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105994,
      "name": "acpi_ev_install_gpe_handler.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584173363,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:750",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172879,
      "name": "acpi_ev_install_gpe_handler.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 384
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584475403,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:750",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475403,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584699632,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584699632,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584799742,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799742,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585002536,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002536,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585138539,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585138539,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843615,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843615,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964766,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964766,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841855,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841855,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586328540,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328540,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587574957,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574957,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588862672,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588862672,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589152096,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589152096,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458368,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458368,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585041079,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585040602,
      "name": "acpi_ev_install_gpe_handler.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584956545,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584956165,
      "name": "acpi_ev_install_gpe_handler.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585090123,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090123,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```

```json
{
  "name": "acpi_ev_install_gpe_handler",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585196283,
      "name": "acpi_ev_install_gpe_handler",
      "external": false,
      "loc": "drivers/acpi/acpica/evxface.c:716",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_raw_handler",
        "drivers/acpi/acpica/evxface.c:acpi_install_gpe_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585196283,
      "name": "acpi_ev_install_gpe_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
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
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
acpi_status acpi_ev_install_gpe_handler(acpi_handle gpe_device, u32 gpe_number, u32 type, u8 is_raw_handler, acpi_gpe_handler address, void * context)
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
