# Function: <code>ghes_edac_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "include/acpi/ghes.h:69",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "include/acpi/ghes.h:69",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "include/acpi/ghes.h:69",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "include/acpi/ghes.h:75",
      "file": "drivers/acpi/apei/ghes.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587052272,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:518",
      "file": "drivers/edac/ghes_edac.c",
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
      "addr": 18446744071587052272,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587350512,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:528",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587350512,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587529056,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:551",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529056,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587803088,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:549",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803088,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588007968,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:584",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007968,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588861568,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:565",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588861568,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 194
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588877120,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:641",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877120,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588763824,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:641",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588763824,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:641",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592652772,
      "name": "ghes_edac_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589455296,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:520",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594537344,
      "name": "ghes_edac_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071590931760,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071632006410,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:507",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_exit"
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
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071623891482,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:507",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_exit"
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
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071626364890,
      "name": "ghes_edac_unregister",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:507",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/edac/ghes_edac.c:ghes_edac_exit"
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501253384,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:584",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501253384,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587964112,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:584",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964112,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void ghes_edac_unregister(struct ghes * ghes)
```

```json
{
  "name": "ghes_edac_unregister",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588079488,
      "name": "ghes_edac_unregister",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:584",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079488,
      "name": "ghes_edac_unregister",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void ghes_edac_unregister(struct ghes * ghes)
```
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void ghes_edac_unregister(struct ghes * ghes)
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
void ghes_edac_unregister(struct ghes * ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void ghes_edac_unregister(struct ghes * ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void ghes_edac_unregister(struct ghes * ghes)
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
void ghes_edac_unregister(struct ghes * ghes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void ghes_edac_unregister(struct ghes * ghes)
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
