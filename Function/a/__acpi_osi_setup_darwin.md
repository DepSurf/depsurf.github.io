# Function: <code>__acpi_osi_setup_darwin</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595412518,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:131",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:dmi_enable_osi_darwin",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595412518,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 86
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595662368,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:131",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:dmi_enable_osi_darwin",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595662368,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596585720,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:131",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:dmi_enable_osi_darwin",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596585720,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602914179,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:132",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:acpi_osi_setup_darwin"
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071603085697,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:149",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071603085697,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604887980,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:156",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604887980,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604994056,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604994056,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605031289,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605031289,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609320268,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609320268,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612390940,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612390940,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614532425,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614532425,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 91
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615483333,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615483333,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 91
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617285521,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617285521,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 101
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
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627999075,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:119",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
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
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619764739,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:119",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
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
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622072195,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:119",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
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
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511112220,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604936421,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604936421,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604903701,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604903701,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605013877,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605013877,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
void __acpi_osi_setup_darwin(bool enable)
```

```json
{
  "name": "__acpi_osi_setup_darwin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071605035469,
      "name": "__acpi_osi_setup_darwin",
      "external": false,
      "loc": "drivers/acpi/osi.c:143",
      "file": "drivers/acpi/osi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osi.c:early_acpi_osi_init",
        "drivers/acpi/osi.c:osi_setup",
        "drivers/acpi/osi.c:osi_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071605035469,
      "name": "__acpi_osi_setup_darwin",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 95
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
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
void __acpi_osi_setup_darwin(bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __acpi_osi_setup_darwin(bool enable)
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
