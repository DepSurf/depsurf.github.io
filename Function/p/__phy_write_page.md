# Function: <code>__phy_write_page</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586408817,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:379",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586552593,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586802642,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:656",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586948706,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587765120,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:710",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587765120,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824304,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:757",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824304,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703728,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:757",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703728,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:758",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295376,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071592542808,
      "name": "__phy_write_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:753",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682640,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071594422261,
      "name": "__phy_write_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:836",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591295408,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071596266765,
      "name": "__phy_write_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:839",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591654048,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071596794861,
      "name": "__phy_write_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int __phy_write_page(struct phy_device * phydev, int page)
```

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:977",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_write_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged",
        "drivers/net/phy/phy-core.c:phy_read_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394880,
      "name": "__phy_write_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071597718038,
      "name": "__phy_write_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499932608,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232476684,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293251808,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277018186,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586705714,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586574034,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586903266,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
  "name": "__phy_write_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587009650,
      "name": "__phy_write_page",
      "external": false,
      "loc": "drivers/net/phy/phy-core.c:695",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_restore_page",
        "drivers/net/phy/phy-core.c:phy_select_page"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __phy_write_page(struct phy_device * phydev, int page)
```
</details>
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
