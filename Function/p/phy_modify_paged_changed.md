# Function: <code>phy_modify_paged_changed</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948944,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948944,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587766853,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:852",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587767040,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826062,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:899",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587826224,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587705482,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:899",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705632,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297306,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:900",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297456,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589684349,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:895",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589684512,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591297549,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:978",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591297312,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656189,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:981",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591655952,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592398269,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:1119",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592398448,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499932904,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499932904,
      "name": "phy_modify_paged_changed",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232476912,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232476912,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293252224,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293252224,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277018444,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277018444,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586705952,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705952,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574272,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574272,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586903504,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586903504,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "phy_modify_paged_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009888,
      "name": "phy_modify_paged_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:834",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009888,
      "name": "phy_modify_paged_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int phy_modify_paged_changed(struct phy_device * phydev, int page, u32 regnum, u16 mask, u16 set)
```
</details>
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
