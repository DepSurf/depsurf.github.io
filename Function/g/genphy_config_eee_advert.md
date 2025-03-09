# Function: <code>genphy_config_eee_advert</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585642786,
      "name": "genphy_config_eee_advert",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1207",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_aneg"
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
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585728611,
      "name": "genphy_config_eee_advert",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1255",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_aneg"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586162291,
      "name": "genphy_config_eee_advert",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1307",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:genphy_config_aneg"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586414949,
      "name": "genphy_config_eee_advert",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1360",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586559581,
      "name": "genphy_config_eee_advert",
      "external": false,
      "loc": "drivers/net/phy/phy_device.c:1543",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586808288,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1628",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586808288,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954432,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954432,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587781109,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1874",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771520,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587840661,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1911",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587830688,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587719877,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1933",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709744,
      "name": "genphy_config_eee_advert",
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588312789,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1979",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302096,
      "name": "genphy_config_eee_advert",
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589701125,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:2008",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589690640,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591315285,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:2026",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:__genphy_config_aneg"
      ],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304176,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591662816,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:2065",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591662816,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592405104,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:2072",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592405104,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499940152,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499940152,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232483152,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232483152,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293261056,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293261056,
      "name": "genphy_config_eee_advert",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277024286,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277024286,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711440,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711440,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586579744,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579744,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586908992,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908992,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int genphy_config_eee_advert(struct phy_device * phydev)
```

```json
{
  "name": "genphy_config_eee_advert",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015376,
      "name": "genphy_config_eee_advert",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1626",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015376,
      "name": "genphy_config_eee_advert",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int genphy_config_eee_advert(struct phy_device * phydev)
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
