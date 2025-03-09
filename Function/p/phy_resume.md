# Function: <code>phy_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585050464,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:787",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/mdio_bus.c:mdio_bus_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050464,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585442976,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1026",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume"
      ],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437984,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585645013,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1109",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume"
      ],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639424,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585731132,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1124",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725456,
      "name": "phy_resume",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586161728,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1181",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586161728,
      "name": "phy_resume",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586410528,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1210",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410528,
      "name": "phy_resume",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586554496,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1387",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554496,
      "name": "phy_resume",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586807360,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1485",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586807360,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586954368,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954368,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587780135,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1707",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771456,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587839722,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1744",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587830624,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587715696,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1763",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715696,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588308448,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1810",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588308448,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589699554,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1839",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589696688,
      "name": "phy_resume",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591314354,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1857",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309840,
      "name": "phy_resume",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591673911,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1896",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct",
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591670032,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592416311,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1903",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:mdio_bus_phy_resume"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592412480,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499940080,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499940080,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232483088,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232483088,
      "name": "phy_resume",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293260944,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293260944,
      "name": "phy_resume",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277024212,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277024212,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586711376,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586711376,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586579680,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586579680,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586908928,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586908928,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
int phy_resume(struct phy_device * phydev)
```

```json
{
  "name": "phy_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015312,
      "name": "phy_resume",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1493",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_attach_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015312,
      "name": "phy_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
