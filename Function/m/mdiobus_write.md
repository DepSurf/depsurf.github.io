# Function: <code>mdiobus_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585058976,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:464",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_setup_forced",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_soft_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058976,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585447200,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:531",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585447200,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585650336,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:540",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585650336,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585736416,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:591",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736416,
      "name": "mdiobus_write",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586170320,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:592",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586170320,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586421520,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:670",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_soft_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586421520,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586567376,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:669",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586567376,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586818656,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:686",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586818656,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586964768,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964768,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587785824,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:961",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587785824,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587844048,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:896",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844048,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587723392,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:895",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587723392,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588316624,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:906",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316624,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589707712,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:913",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589707712,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591322480,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:918",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322480,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591683456,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:1148",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591683456,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592426192,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:1166",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592426192,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499952576,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/broadcom/phy-bcm-ns2-pcie.c:ns2_pci_phy_init",
        "drivers/phy/broadcom/phy-bcm-ns2-pcie.c:ns2_pci_phy_init",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_init",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_restart_autoneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499952576,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232493740,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ksz9021rn_phy_fixup",
        "arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:bcm54220_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232493740,
      "name": "mdiobus_write",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293277104,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293277104,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277034610,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277034610,
      "name": "mdiobus_write",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586721776,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721776,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590080,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586590080,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586919328,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586919328,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int mdiobus_write(struct mii_bus * bus, int addr, u32 regnum, u16 val)
```

```json
{
  "name": "mdiobus_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587025776,
      "name": "mdiobus_write",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:678",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025776,
      "name": "mdiobus_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
