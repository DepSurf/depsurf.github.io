# Function: <code>phy_request_interrupt</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586798457,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:815",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586798457,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586793552,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586944525,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586944525,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586939888,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:908",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587760847,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071587759776,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:967",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591530459,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071587813728,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:968",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591472649,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071587693216,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:994",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592542611,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071588284544,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1026",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594421968,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071589668160,
      "name": "phy_request_interrupt",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591279936,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1055",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591279936,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591636560,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1289",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591636560,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592377152,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1342",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592377152,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499924448,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499924448,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232468464,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232468464,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293240528,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293240528,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277010586,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277010586,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586701533,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701533,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586696896,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586569853,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586569853,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586565232,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586899085,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899085,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071586894448,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void phy_request_interrupt(struct phy_device * phydev)
```

```json
{
  "name": "phy_request_interrupt",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587005469,
      "name": "phy_request_interrupt",
      "external": true,
      "loc": "drivers/net/phy/phy.c:796",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005469,
      "name": "phy_request_interrupt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 90
    },
    {
      "addr": 18446744071587000832,
      "name": "phy_request_interrupt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void phy_request_interrupt(struct phy_device * phydev)
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
