# Function: <code>gnttab_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583845952,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1035",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583845952,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584175552,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1034",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584175552,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584356944,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1034",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584356944,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584440336,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1035",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440336,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584849216,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1227",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849216,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1227",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585082384,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585084529,
      "name": "gnttab_setup.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585195079,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585190880,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585195079,
      "name": "gnttab_setup.cold.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585407329,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585402400,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585407329,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585544160,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585548065,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1352",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261872,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071586266440,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1475",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380144,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071591447380,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1475",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263808,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071591388834,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1482",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586774864,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071592432464,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1546",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588053552,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    },
    {
      "addr": 18446744071594300611,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432336,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1549",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432336,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589731472,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1567",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589731472,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069440,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1565",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069440,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498201160,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498201160,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306192,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585310097,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494560,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585498465,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
int gnttab_setup()
```

```json
{
  "name": "gnttab_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_setup",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1355",
      "file": "drivers/xen/grant-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602592,
      "name": "gnttab_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    },
    {
      "addr": 18446744071585606497,
      "name": "gnttab_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
int gnttab_setup()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int gnttab_setup()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int gnttab_setup()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int gnttab_setup()
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
