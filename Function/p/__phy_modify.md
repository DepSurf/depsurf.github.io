# Function: <code>__phy_modify</code>

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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586409056,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:337",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409056,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586552832,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:508",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586552832,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586802945,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:511",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_paged",
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802176,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586948603,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948240,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587764910,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:562",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764800,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587824094,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:609",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823984,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587703518,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:609",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703408,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588295150,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:610",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588295040,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589682414,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:605",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682288,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591294990,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:688",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294848,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591653630,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:691",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591653488,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592394414,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:829",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592394272,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499932508,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499932064,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232476604,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232476256,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293251664,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293251056,
      "name": "__phy_modify",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277018090,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277017682,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586705611,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586705248,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586573931,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573568,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586903163,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586902800,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587009547,
      "name": "__phy_modify",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:550",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009184,
      "name": "__phy_modify",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int __phy_modify(struct phy_device * phydev, u32 regnum, u16 mask, u16 set)
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
