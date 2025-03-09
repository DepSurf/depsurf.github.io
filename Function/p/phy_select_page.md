# Function: <code>phy_select_page</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586408672,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
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
      "addr": 18446744071586408672,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552448,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:581",
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
      "addr": 18446744071586552448,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802272,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:687",
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
      "addr": 18446744071586802272,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948336,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948336,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587766853,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:744",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765216,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826062,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:791",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824400,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587705482,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:791",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703824,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297306,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:792",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295488,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589684349,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:787",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682752,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591297549,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:870",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295536,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656189,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:873",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654176,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592398269,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:1011",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592395008,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499932216,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499932216,
      "name": "phy_select_page",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232476344,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232476344,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293251232,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293251232,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277017820,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277017820,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586705344,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705344,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573664,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573664,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902896,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902896,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int phy_select_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "phy_select_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009280,
      "name": "phy_select_page",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:726",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009280,
      "name": "phy_select_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int phy_select_page(struct phy_device * phydev, int page)
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
