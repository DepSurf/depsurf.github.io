# Function: <code>acpi_node_get_parent</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136784,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:966",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136784,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584408144,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:978",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584408144,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633488,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:978",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633488,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584732432,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1066",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584732432,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584931840,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584931840,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067648,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067648,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585772688,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585772688,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585891056,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1107",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585891056,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768080,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1087",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768080,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586250560,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1087",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586250560,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587496149,
      "name": "acpi_node_get_parent",
      "external": false,
      "loc": "drivers/acpi/property.c:1095",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493568,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767445,
      "name": "acpi_node_get_parent",
      "external": false,
      "loc": "drivers/acpi/property.c:1265",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588765504,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589054645,
      "name": "acpi_node_get_parent",
      "external": false,
      "loc": "drivers/acpi/property.c:1253",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054496,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360037,
      "name": "acpi_node_get_parent",
      "external": false,
      "loc": "drivers/acpi/property.c:1321",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent",
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359888,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497471168,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497471168,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584997136,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584997136,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584912720,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584912720,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585019232,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585019232,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```

```json
{
  "name": "acpi_node_get_parent",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585125408,
      "name": "acpi_node_get_parent",
      "external": true,
      "loc": "drivers/acpi/property.c:1092",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/property.c:acpi_fwnode_get_parent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585125408,
      "name": "acpi_node_get_parent",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct fwnode_handle * acpi_node_get_parent(struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct fwnode_handle * acpi_node_get_parent(const struct fwnode_handle * fwnode)
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
