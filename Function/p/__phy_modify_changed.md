# Function: <code>__phy_modify_changed</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802048,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:456",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802048,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948112,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948112,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587766904,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:873",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587826088,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1006",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587705514,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1026",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588297338,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1034",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589684373,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1078",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591297573,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1116",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591656213,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1273",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
  "name": "__phy_modify_changed",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592398293,
      "name": "__phy_modify_changed",
      "external": false,
      "loc": "include/linux/phy.h:1314",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499931928,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499931928,
      "name": "__phy_modify_changed",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232476140,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232476140,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293250848,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293250848,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277017548,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277017548,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586705120,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705120,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586573440,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573440,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586902672,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902672,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009056,
      "name": "__phy_modify_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:495",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged_changed",
        "drivers/net/phy/phy-core.c:phy_modify",
        "drivers/net/phy/phy-core.c:phy_modify_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009056,
      "name": "__phy_modify_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __phy_modify_changed(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
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
