# Function: <code>__ghes_check_estatus</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585072406,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:307",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc",
        "drivers/acpi/apei/ghes.c:__ghes_peek_estatus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072352,
      "name": "__ghes_check_estatus.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071585076683,
      "name": "__ghes_check_estatus.isra.14.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585276793,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:299",
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
      "addr": 18446744071585276736,
      "name": "__ghes_check_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071585280999,
      "name": "__ghes_check_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585414745,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:312",
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
      "addr": 18446744071585414688,
      "name": "__ghes_check_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071585418966,
      "name": "__ghes_check_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:307",
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
      "addr": 18446744071586122928,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071586129017,
      "name": "__ghes_check_estatus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:319",
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
      "addr": 18446744071586242384,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071591442125,
      "name": "__ghes_check_estatus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:319",
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
      "addr": 18446744071586117360,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071591383230,
      "name": "__ghes_check_estatus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:319",
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
      "addr": 18446744071586617168,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071592420573,
      "name": "__ghes_check_estatus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:319",
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
      "addr": 18446744071587881184,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071594288727,
      "name": "__ghes_check_estatus.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589228720,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:335",
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
      "addr": 18446744071589228720,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589525440,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:333",
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
      "addr": 18446744071589525440,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589833472,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:361",
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
      "addr": 18446744071589833472,
      "name": "__ghes_check_estatus",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497688960,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:312",
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
      "addr": 18446603336497688960,
      "name": "__ghes_check_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585365145,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:312",
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
      "addr": 18446744071585365088,
      "name": "__ghes_check_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071585369366,
      "name": "__ghes_check_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
  "name": "__ghes_check_estatus",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585472457,
      "name": "__ghes_check_estatus",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:312",
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
      "addr": 18446744071585472400,
      "name": "__ghes_check_estatus.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071585476710,
      "name": "__ghes_check_estatus.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __ghes_check_estatus(struct ghes * ghes, struct acpi_hest_generic_status * estatus)
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
