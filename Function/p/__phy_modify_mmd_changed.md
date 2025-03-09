# Function: <code>__phy_modify_mmd_changed</code>

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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586803712,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:557",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586803712,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586949808,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949808,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587767560,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:608",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587766320,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587826744,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:655",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825504,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587706151,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:655",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587704928,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588297975,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:656",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296752,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589685063,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:651",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683728,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591298119,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:734",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296656,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591656791,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:737",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591655424,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592399079,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:875",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592397280,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499934032,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499934032,
      "name": "__phy_modify_mmd_changed",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232477828,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232477828,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293253488,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293253488,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277019394,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277019394,
      "name": "__phy_modify_mmd_changed",
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706816,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706816,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575136,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575136,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586904368,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904368,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```

```json
{
  "name": "__phy_modify_mmd_changed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010752,
      "name": "__phy_modify_mmd_changed",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010752,
      "name": "__phy_modify_mmd_changed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int __phy_modify_mmd_changed(struct phy_device * phydev, int devad, u32 regnum, u16 mask, u16 set)
```
</details>
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
