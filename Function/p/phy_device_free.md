# Function: <code>phy_device_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585050672,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:44",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/fixed_phy.c:fixed_phy_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585050672,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585438217,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:44",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438192,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585639657,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:45",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585639632,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725625,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:45",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725600,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586158969,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:45",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158944,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410517,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:45",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586410496,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586554293,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:208",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554272,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586804741,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586804720,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586950965,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950944,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587768208,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:201",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587768208,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587827344,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:201",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827344,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587706800,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:201",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587706800,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588298944,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:202",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588298944,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589686464,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:203",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589686464,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591299712,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:204",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591299712,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591658384,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:236",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591658384,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592400672,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:238",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/phy/mdio_bus.c:__mdiobus_register",
        "drivers/net/mdio/fwnode_mdio.c:fwnode_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592400672,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499935784,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499935712,
      "name": "phy_device_free",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232479340,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232479292,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293255500,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293255408,
      "name": "phy_device_free",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277020834,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan",
        "drivers/of/of_mdio.c:of_phy_deregister_fixed_link",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy",
        "drivers/of/of_mdio.c:of_mdiobus_register_phy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277020770,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586707973,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707952,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586576293,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576272,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586905525,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586905504,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void phy_device_free(struct phy_device * phydev)
```

```json
{
  "name": "phy_device_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587011909,
      "name": "phy_device_free",
      "external": true,
      "loc": "drivers/net/phy/phy_device.c:200",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:phy_mdio_device_free"
      ],
      "caller_func": [
        "drivers/net/phy/mdio_bus.c:mdiobus_scan"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011888,
      "name": "phy_device_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
