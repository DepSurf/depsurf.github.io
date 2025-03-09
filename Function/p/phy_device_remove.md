# Function: <code>phy_device_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585051760,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:418",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585051760,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585439789,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:623",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439744,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585641549,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:671",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585641504,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585727245,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:666",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727200,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586160605,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:666",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586160560,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586412224,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:685",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586412224,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586556048,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:863",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586556048,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586807152,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:878",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586807152,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586953360,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953360,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587776341,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:885",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587770560,
      "name": "phy_device_remove",
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587835669,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:907",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587829712,
      "name": "phy_device_remove",
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587715621,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:924",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708928,
      "name": "phy_device_remove",
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588308286,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:958",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588301216,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589696285,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:989",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689392,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591309741,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:993",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591302768,
      "name": "phy_device_remove",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591669933,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1024",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591661312,
      "name": "phy_device_remove",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592411693,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:1027",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove"
      ],
      "caller_func": [
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592403600,
      "name": "phy_device_remove",
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499938864,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499938864,
      "name": "phy_device_remove",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232481976,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232481976,
      "name": "phy_device_remove",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293259312,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293259312,
      "name": "phy_device_remove",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277023170,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277023170,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586710368,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586710368,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586578688,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578688,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907920,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907920,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void phy_device_remove(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587014304,
      "name": "phy_device_remove",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:886",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_remove",
        "drivers/net/phy/fixed_phy.c:fixed_phy_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014304,
      "name": "phy_device_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
