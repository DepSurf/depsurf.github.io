# Function: <code>ec_remove_handlers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583582335,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1324",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583904034,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1338",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove",
        "drivers/acpi/ec.c:acpi_ec_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583904034,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584044646,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1444",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584044646,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097632,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097632,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584369104,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1470",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584369104,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584590368,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071584597021,
      "name": "ec_remove_handlers.cold.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1488",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584687776,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071584694525,
      "name": "ec_remove_handlers.cold.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584888337,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1502",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585024081,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1519",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725840,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071585733122,
      "name": "ec_remove_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1506",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585847904,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071591433795,
      "name": "ec_remove_handlers.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585726513,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1507",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586208225,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1524",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587445742,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1530",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588704784,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1535",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588704784,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992992,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1554",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992992,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void ec_remove_handlers(struct acpi_ec * ec)
```

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589297248,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1554",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589297248,
      "name": "ec_remove_handlers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497435732,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584966465,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584875265,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584975665,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ec_remove_handlers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585081841,
      "name": "ec_remove_handlers",
      "external": false,
      "loc": "drivers/acpi/ec.c:1476",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_remove"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```
</details>
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void ec_remove_handlers(struct acpi_ec * ec)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
