# Function: <code>__ghes_panic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583786628,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:826",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584112733,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:831",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584260701,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:831",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584335024,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:718",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335024,
      "name": "__ghes_panic.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584739328,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:674",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739328,
      "name": "__ghes_panic.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:690",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_notify_nmi",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967952,
      "name": "__ghes_panic.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    },
    {
      "addr": 18446744071584971973,
      "name": "__ghes_panic.isra.13.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:701",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072880,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071585076793,
      "name": "__ghes_panic.cold.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585279335,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:693",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281082,
      "name": "__ghes_panic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585417271,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:706",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585419049,
      "name": "__ghes_panic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:730",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586124128,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071586129127,
      "name": "__ghes_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:793",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586243648,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071591442235,
      "name": "__ghes_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:840",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586118480,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071591383317,
      "name": "__ghes_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:840",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618352,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    },
    {
      "addr": 18446744071592420752,
      "name": "__ghes_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:840",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882768,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071594288911,
      "name": "__ghes_panic.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589230512,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:862",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589230512,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589527232,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:860",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589527232,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589835984,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:898",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589835984,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497691216,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:706",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497691216,
      "name": "__ghes_panic",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585367671,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:706",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585369449,
      "name": "__ghes_panic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_panic",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585474999,
      "name": "__ghes_panic",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:706",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476793,
      "name": "__ghes_panic.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void __ghes_panic(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 buf_paddr, enum fixed_addresses fixmap_idx)
```
</details>
</li>
</ul>
