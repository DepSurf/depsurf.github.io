# Function: <code>ghes_do_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583784480,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:423",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583784480,
      "name": "ghes_do_proc.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 769
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584110560,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:428",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110560,
      "name": "ghes_do_proc.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584258512,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:428",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258512,
      "name": "ghes_do_proc.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584336736,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:461",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336736,
      "name": "ghes_do_proc.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
void ghes_do_proc(struct ghes * ghes, const struct acpi_hest_generic_status * estatus)
```

```json
{
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584740976,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:417",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584740976,
      "name": "ghes_do_proc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:462",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969520,
      "name": "ghes_do_proc.isra.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 986
    },
    {
      "addr": 18446744071584972047,
      "name": "ghes_do_proc.isra.14.cold.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:488",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073840,
      "name": "ghes_do_proc.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
    },
    {
      "addr": 18446744071585076826,
      "name": "ghes_do_proc.isra.17.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:480",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278048,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1022
    },
    {
      "addr": 18446744071585281129,
      "name": "ghes_do_proc.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:493",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585416000,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
    },
    {
      "addr": 18446744071585419096,
      "name": "ghes_do_proc.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586125440,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:514",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586125440,
      "name": "ghes_do_proc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 705
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586245152,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:576",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586245152,
      "name": "ghes_do_proc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 746
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:625",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119744,
      "name": "ghes_do_proc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1453
    },
    {
      "addr": 18446744071591383406,
      "name": "ghes_do_proc.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:625",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586619696,
      "name": "ghes_do_proc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1487
    },
    {
      "addr": 18446744071592420841,
      "name": "ghes_do_proc.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:625",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587884224,
      "name": "ghes_do_proc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1455
    },
    {
      "addr": 18446744071594288996,
      "name": "ghes_do_proc.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589232656,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:641",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589232656,
      "name": "ghes_do_proc.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1281
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589529392,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:639",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589529392,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1269
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589837888,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:676",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837888,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497689800,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:493",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497689800,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:493",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585366400,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
    },
    {
      "addr": 18446744071585369496,
      "name": "ghes_do_proc.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
  "name": "ghes_do_proc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_do_proc",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:493",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_proc_in_irq",
        "drivers/acpi/apei/ghes.c:ghes_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585473728,
      "name": "ghes_do_proc.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1006
    },
    {
      "addr": 18446744071585476840,
      "name": "ghes_do_proc.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
void ghes_do_proc(struct ghes * ghes, const struct acpi_hest_generic_status * estatus)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void ghes_do_proc(struct ghes * ghes, const struct acpi_hest_generic_status * estatus)
```
</details>
</li>
</ul>
