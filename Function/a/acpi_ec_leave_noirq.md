# Function: <code>acpi_ec_leave_noirq</code>

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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584037806,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1857",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq"
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584103010,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1001",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584374490,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1003",
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584587296,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1003",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587296,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584684704,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1003",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684704,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584885104,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1017",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885104,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585021136,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1009",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585021136,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585724610,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1005",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585846674,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:992",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585725202,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:993",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586207636,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:995",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587445604,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1018",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588706324,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1015",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588994532,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1000",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589298788,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1000",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497433160,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1009",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq"
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584963520,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1009",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584963520,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584872320,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1009",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584872320,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972720,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1009",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972720,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_leave_noirq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585078896,
      "name": "acpi_ec_leave_noirq",
      "external": false,
      "loc": "drivers/acpi/ec.c:1009",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_resume_noirq",
        "drivers/acpi/ec.c:ec_install_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585078896,
      "name": "acpi_ec_leave_noirq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
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
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec * ec)
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
