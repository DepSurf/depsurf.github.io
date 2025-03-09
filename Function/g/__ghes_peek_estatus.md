# Function: <code>__ghes_peek_estatus</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __ghes_peek_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 * buf_paddr, enum fixed_addresses fixmap_idx)
```

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:331",
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
      "addr": 18446744071585072496,
      "name": "__ghes_peek_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071585076749,
      "name": "__ghes_peek_estatus.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:323",
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
      "addr": 18446744071585276560,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585280971,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:336",
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
      "addr": 18446744071585414512,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585418938,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:331",
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
      "addr": 18446744071586124448,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071586129188,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:343",
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
      "addr": 18446744071586243968,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591442296,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:343",
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
      "addr": 18446744071586118800,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071591383378,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:343",
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
      "addr": 18446744071586618672,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071592420813,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:343",
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
      "addr": 18446744071587883104,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
    },
    {
      "addr": 18446744071594288974,
      "name": "__ghes_peek_estatus.isra.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589230928,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:359",
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
      "addr": 18446744071589230928,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589527648,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:357",
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
      "addr": 18446744071589527648,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589836448,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:385",
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
      "addr": 18446744071589836448,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497688760,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:336",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_in_nmi_queue_one_entry",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497688760,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:336",
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
      "addr": 18446744071585364912,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585369338,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
  "name": "__ghes_peek_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_peek_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:336",
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
      "addr": 18446744071585472224,
      "name": "__ghes_peek_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071585476682,
      "name": "__ghes_peek_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int __ghes_peek_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 * buf_paddr, enum fixed_addresses fixmap_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int __ghes_peek_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus, u64 * buf_paddr, enum fixed_addresses fixmap_idx)
```
</details>
</li>
</ul>
