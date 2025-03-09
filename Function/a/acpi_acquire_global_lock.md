# Function: <code>acpi_acquire_global_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583640941,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1052",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640941,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964008,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1051",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964008,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584105639,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1051",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105639,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584170709,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1051",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584170709,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471798,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1051",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471798,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584695955,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695955,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796054,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796054,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998830,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998830,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585134833,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585134833,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843118,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843118,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964269,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964269,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585841358,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585841358,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586328043,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328043,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587574407,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587574407,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588861984,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588861984,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151408,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151408,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589457632,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589457632,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_acquire_global_lock",
      "external": false,
      "loc": "include/acpi/acpixf.h:666",
      "file": "drivers/acpi/ec.c",
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
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585038336,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585038336,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584953902,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584953902,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086417,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086417,
      "name": "acpi_acquire_global_lock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```

```json
{
  "name": "acpi_acquire_global_lock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585192577,
      "name": "acpi_acquire_global_lock",
      "external": true,
      "loc": "drivers/acpi/acpica/evxface.c:1026",
      "file": "drivers/acpi/acpica/evxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585192577,
      "name": "acpi_acquire_global_lock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 * handle)
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
