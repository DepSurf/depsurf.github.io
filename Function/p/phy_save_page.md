# Function: <code>phy_save_page</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586408677,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:392",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586408608,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586552453,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:563",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552384,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586802277,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:669",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802208,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586948341,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948272,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587764992,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764992,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824176,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:773",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824176,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703600,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:773",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703600,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:774",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592542787,
      "name": "phy_save_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071588295232,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:769",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594422241,
      "name": "phy_save_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589682512,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:852",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596266745,
      "name": "phy_save_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591295264,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:855",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596794841,
      "name": "phy_save_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071591653904,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:993",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597718018,
      "name": "phy_save_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592394736,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499932248,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499932152,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232476364,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232476288,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293251272,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293251120,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277017848,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277017760,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586705349,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705280,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586573669,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573600,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586902901,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902832,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int phy_save_page(struct phy_device * phydev)
```

```json
{
  "name": "phy_save_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587009285,
      "name": "phy_save_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:708",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_select_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009216,
      "name": "phy_save_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int phy_save_page(struct phy_device * phydev)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
