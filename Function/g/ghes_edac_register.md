# Function: <code>ghes_edac_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "include/acpi/ghes.h:64",
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
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "include/acpi/ghes.h:64",
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
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "include/acpi/ghes.h:64",
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
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "include/acpi/ghes.h:70",
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587051616,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:430",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587051616,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:436",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587350593,
      "name": "ghes_edac_register.cold.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    },
    {
      "addr": 18446744071587350080,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 417
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:459",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587529137,
      "name": "ghes_edac_register.cold.3",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071587528624,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:457",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803174,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    },
    {
      "addr": 18446744071587802672,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:474",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588008179,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071588007440,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:455",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588861790,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071588861024,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:508",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591595384,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
    },
    {
      "addr": 18446744071588876336,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 783
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:508",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591538532,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
    },
    {
      "addr": 18446744071588763040,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 770
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:508",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592652436,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071589454496,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:387",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594537005,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
    },
    {
      "addr": 18446744071590930896,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 855
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
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:388",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592630736,
      "name": "ghes_edac_register.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    },
    {
      "addr": 18446744071596312952,
      "name": "ghes_edac_register.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:388",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593061360,
      "name": "ghes_edac_register.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
    },
    {
      "addr": 18446744071596841841,
      "name": "ghes_edac_register.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "ghes_edac_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": false,
      "loc": "drivers/edac/ghes_edac.c:388",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/edac/ghes_edac.c:ghes_edac_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593813248,
      "name": "ghes_edac_register.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1032
    },
    {
      "addr": 18446744071597766842,
      "name": "ghes_edac_register.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501252736,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:474",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501252736,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:474",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964323,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071587963584,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```

```json
{
  "name": "ghes_edac_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ghes_edac_register",
      "external": true,
      "loc": "drivers/edac/ghes_edac.c:474",
      "file": "drivers/edac/ghes_edac.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/apei/ghes.c:ghes_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588079699,
      "name": "ghes_edac_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
    },
    {
      "addr": 18446744071588078960,
      "name": "ghes_edac_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
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
int ghes_edac_register(struct ghes * ghes, struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int ghes_edac_register(struct ghes * ghes, struct device * dev)
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
