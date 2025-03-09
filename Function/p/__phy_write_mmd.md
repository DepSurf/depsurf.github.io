# Function: <code>__phy_write_mmd</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586803520,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:393",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586803520,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586949616,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949616,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587764304,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:477",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764304,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587823488,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:524",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823488,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587702912,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:524",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587702912,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588294544,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:525",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294544,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589681728,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:520",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589681728,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591294240,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:603",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294240,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591652880,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:606",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591652880,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592396976,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:618",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:phy_modify_mmd",
        "drivers/net/phy/phy-core.c:phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396976,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499933792,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499933792,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232477640,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232477640,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293253216,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293253216,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277019184,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277019184,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586706624,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706624,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586574944,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574944,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586904176,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904176,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "__phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587010560,
      "name": "__phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-core.c:__phy_modify_mmd_changed",
        "drivers/net/phy/phy-core.c:phy_write_mmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010560,
      "name": "__phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
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
