# Function: <code>gnttab_request_version</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583848214,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1025",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
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
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584177270,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1024",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
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
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584358646,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1024",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
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
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584440454,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1025",
      "file": "drivers/xen/grant-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_init",
        "drivers/xen/grant-table.c:gnttab_resume"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851520,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1204",
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
      "addr": 18446744071584851520,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1204",
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
      "addr": 18446744071585080128,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071585084355,
      "name": "gnttab_request_version.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585195110,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446744071585191984,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    },
    {
      "addr": 18446744071585195103,
      "name": "gnttab_request_version.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585407360,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446744071585403536,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071585407353,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585548094,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446744071585545296,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071585548087,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1329",
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
      "addr": 18446744071586262992,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071586266462,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1452",
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
      "addr": 18446744071586381264,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071591447402,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1452",
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
      "addr": 18446744071586266384,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071591389277,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1459",
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
      "addr": 18446744071586776896,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
    },
    {
      "addr": 18446744071592432535,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594300640,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1523",
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
      "addr": 18446744071588055536,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
    },
    {
      "addr": 18446744071594300633,
      "name": "gnttab_request_version.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589435216,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1526",
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
      "addr": 18446744071589435216,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589734352,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1544",
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
      "addr": 18446744071589734352,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590074160,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1542",
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
      "addr": 18446744071590074160,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498200424,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446603336498200424,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585310126,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446744071585307328,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071585310119,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585498494,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446744071585495696,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071585498487,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void gnttab_request_version()
```

```json
{
  "name": "gnttab_request_version",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585606526,
      "name": "gnttab_request_version",
      "external": false,
      "loc": "drivers/xen/grant-table.c:1332",
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
      "addr": 18446744071585603728,
      "name": "gnttab_request_version",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    },
    {
      "addr": 18446744071585606519,
      "name": "gnttab_request_version.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
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
void gnttab_request_version()
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
void gnttab_request_version()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void gnttab_request_version()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void gnttab_request_version()
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
void gnttab_request_version()
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
