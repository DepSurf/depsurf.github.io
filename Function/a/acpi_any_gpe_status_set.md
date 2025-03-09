# Function: <code>acpi_any_gpe_status_set</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 acpi_any_gpe_status_set()
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585144333,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:810",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585144333,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585850219,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850219,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585971370,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585971370,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585848438,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585848438,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586335285,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586335285,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587580778,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587580778,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588869456,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588869456,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589158896,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589158896,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
u32 acpi_any_gpe_status_set(u32 gpe_skip_number)
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589465216,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:811",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589465216,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
u32 acpi_any_gpe_status_set()
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585043602,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:810",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043602,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
u32 acpi_any_gpe_status_set()
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584959162,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:810",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584959162,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
u32 acpi_any_gpe_status_set()
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585095917,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:810",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585095917,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
u32 acpi_any_gpe_status_set()
```

```json
{
  "name": "acpi_any_gpe_status_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585202077,
      "name": "acpi_any_gpe_status_set",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfgpe.c:810",
      "file": "drivers/acpi/acpica/evxfgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202077,
      "name": "acpi_any_gpe_status_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
u32 acpi_any_gpe_status_set()
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 gpe_skip_number</code>
</li>
</ul>
</details>
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
u32 acpi_any_gpe_status_set()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 acpi_any_gpe_status_set()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 acpi_any_gpe_status_set()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 acpi_any_gpe_status_set()
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
