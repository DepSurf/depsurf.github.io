# Function: <code>acpi_hw_get_access_bit_width</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996570,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:84",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996235,
      "name": "acpi_hw_get_access_bit_width.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584138018,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:84",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137683,
      "name": "acpi_hw_get_access_bit_width.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204792,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:86",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204792,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534082,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:86",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534082,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758410,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758410,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859170,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859170,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585062918,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062918,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199252,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199252,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904753,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904753,
      "name": "acpi_hw_get_access_bit_width",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026367,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026367,
      "name": "acpi_hw_get_access_bit_width",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585903372,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903372,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586390899,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390899,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639701,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639701,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588940688,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071596220663,
      "name": "acpi_hw_get_access_bit_width.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230704,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071596747243,
      "name": "acpi_hw_get_access_bit_width.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537216,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 293
    },
    {
      "addr": 18446744071597655871,
      "name": "acpi_hw_get_access_bit_width.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497540248,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497540248,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073758,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073758,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989232,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989232,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585150836,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585150836,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```

```json
{
  "name": "acpi_hw_get_access_bit_width",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585256996,
      "name": "acpi_hw_get_access_bit_width",
      "external": false,
      "loc": "drivers/acpi/acpica/hwregs.c:50",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_validate_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256996,
      "name": "acpi_hw_get_access_bit_width",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u8 acpi_hw_get_access_bit_width(u64 address, struct acpi_generic_address * reg, u8 max_bit_width)
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
