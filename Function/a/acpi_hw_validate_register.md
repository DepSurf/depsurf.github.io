# Function: <code>acpi_hw_validate_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583672934,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:83",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672934,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583996287,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:124",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583996287,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584137735,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:124",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwxface.c:acpi_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584137735,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204975,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:158",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read",
        "drivers/acpi/acpica/hwxface.c:acpi_write",
        "drivers/acpi/acpica/hwxface.c:acpi_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204975,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534265,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:158",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534265,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584758593,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584758593,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859353,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859353,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063101,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063101,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199435,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199435,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585904942,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585904942,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586026556,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586026556,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585903563,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585903563,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586391177,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586391177,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639940,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639940,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588941008,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588941008,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231024,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231024,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589537536,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589537536,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497540512,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497540512,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073941,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073941,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989415,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989415,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151019,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151019,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```

```json
{
  "name": "acpi_hw_validate_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585257179,
      "name": "acpi_hw_validate_register",
      "external": true,
      "loc": "drivers/acpi/acpica/hwregs.c:122",
      "file": "drivers/acpi/acpica/hwregs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwregs.c:acpi_hw_write",
        "drivers/acpi/acpica/hwregs.c:acpi_hw_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585257179,
      "name": "acpi_hw_validate_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_hw_validate_register(struct acpi_generic_address * reg, u8 max_bit_width, u64 * address)
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
