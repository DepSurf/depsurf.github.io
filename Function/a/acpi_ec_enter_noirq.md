# Function: <code>acpi_ec_enter_noirq</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584037907,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1842",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq"
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
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584102855,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:990",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584374321,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:992",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584587200,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:992",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587200,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684608,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:992",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684608,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584885008,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1006",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885008,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585020960,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:998",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020960,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585723969,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:994",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585846033,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:981",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585724721,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:982",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586206720,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:984",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587444448,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1007",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588705392,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1004",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588993600,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:989",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589297856,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:989",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497433512,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:998",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497433512,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584963344,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:998",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963344,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584872144,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:998",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872144,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972544,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:998",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972544,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_enter_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585078720,
      "name": "acpi_ec_enter_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:998",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078720,
      "name": "acpi_ec_enter_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```
</details>
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
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec * ec)
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
