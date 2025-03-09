# Function: <code>mdiobus_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585058768,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:411",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058768,
      "name": "mdiobus_read",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585446992,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:478",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585446992,
      "name": "mdiobus_read",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585649648,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:483",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585649648,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585736640,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:534",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585736640,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586169600,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:535",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_resume",
        "drivers/net/phy/phy_device.c:genphy_suspend",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_restart_aneg",
        "drivers/net/phy/phy_device.c:genphy_setup_forced",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586169600,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586422208,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:617",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586422208,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586566688,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:616",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_soft_reset",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566688,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586817968,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:633",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_config_init",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586817968,
      "name": "mdiobus_read",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586964080,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964080,
      "name": "mdiobus_read",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587786432,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:906",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:phy_poll_reset",
        "drivers/net/phy/phy_device.c:phy_poll_reset",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587786432,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587844576,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:847",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:phy_poll_reset",
        "drivers/net/phy/phy_device.c:phy_poll_reset",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844576,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587724688,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:846",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724688,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588318048,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:857",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318048,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589705248,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:864",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:__genphy_config_aneg",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589705248,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591324240,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:869",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:get_phy_c45_ids",
        "drivers/net/phy/phy_device.c:phy_c45_probe_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591324240,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591684288,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:1049",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591684288,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592427024,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:1067",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_loopback",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_c37_read_status",
        "drivers/net/phy/phy_device.c:genphy_read_status_fixed",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_read_master_slave",
        "drivers/net/phy/phy_device.c:genphy_config_advert",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592427024,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499952040,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/ethernet/freescale/fman/fman_dtsec.c:dtsec_restart_autoneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499952040,
      "name": "mdiobus_read",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232494640,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8035_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6q.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx6sx.c:ar8031_phy_fixup",
        "arch/arm/mach-imx/mach-imx7d.c:ar8031_phy_fixup",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232494640,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293278608,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293278608,
      "name": "mdiobus_read",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277035386,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_read_lpa",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277035386,
      "name": "mdiobus_read",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586721088,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586721088,
      "name": "mdiobus_read",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586589392,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586589392,
      "name": "mdiobus_read",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586918640,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918640,
      "name": "mdiobus_read",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int mdiobus_read(struct mii_bus * bus, int addr, u32 regnum)
```

```json
{
  "name": "mdiobus_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587025056,
      "name": "mdiobus_read",
      "external": true,
      "loc": "drivers/net/phy/mdio_bus.c:625",
      "file": "drivers/net/phy/mdio_bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_read_abilities",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_update_link",
        "drivers/net/phy/phy_device.c:genphy_aneg_done",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_device",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg",
        "drivers/net/phy/phy_device.c:get_phy_c45_devs_in_pkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587025056,
      "name": "mdiobus_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
