# Function: <code>ghes_fini</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583784053,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:273",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584110104,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:278",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584258056,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:278",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584334272,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:310",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584334272,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584738592,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:266",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584738592,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584967232,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:266",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967232,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585071888,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:257",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585071888,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585276064,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:249",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585276064,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585414016,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:262",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585414016,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586125220,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:257",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586244932,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:269",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586119524,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:269",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586619476,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:269",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587883993,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:269",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589232373,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:285",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589529008,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:283",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589837504,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:311",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
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
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497688184,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:262",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497688184,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364416,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:262",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364416,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ghes_fini(struct ghes * ghes)
```

```json
{
  "name": "ghes_fini",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585471728,
      "name": "ghes_fini",
      "external": false,
      "loc": "drivers/acpi/apei/ghes.c:262",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471728,
      "name": "ghes_fini",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void ghes_fini(struct ghes * ghes)
```
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void ghes_fini(struct ghes * ghes)
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
void ghes_fini(struct ghes * ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ghes_fini(struct ghes * ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ghes_fini(struct ghes * ghes)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void ghes_fini(struct ghes * ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void ghes_fini(struct ghes * ghes)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
