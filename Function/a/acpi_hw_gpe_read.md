# Function: <code>acpi_hw_gpe_read</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586024616,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024616,
      "name": "acpi_hw_gpe_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585901632,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585901632,
      "name": "acpi_hw_gpe_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586389127,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389127,
      "name": "acpi_hw_gpe_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587637717,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587637717,
      "name": "acpi_hw_gpe_read",
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
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588938288,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938288,
      "name": "acpi_hw_gpe_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589228288,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589228288,
      "name": "acpi_hw_gpe_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```

```json
{
  "name": "acpi_hw_gpe_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589534800,
      "name": "acpi_hw_gpe_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwgpe.c:43",
      "file": "drivers/acpi/acpica/hwgpe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/evgpe.c:acpi_ev_detect_gpe",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_block_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_get_gpe_status",
        "drivers/acpi/acpica/hwgpe.c:acpi_hw_low_set_gpe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589534800,
      "name": "acpi_hw_gpe_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_hw_gpe_read(u64 * value, struct acpi_gpe_address * reg)
```
</details>
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
