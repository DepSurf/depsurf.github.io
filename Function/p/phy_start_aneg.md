# Function: <code>phy_start_aneg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585044992,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:481",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_state_machine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585044992,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432128,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432128,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585633200,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:602",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585633200,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585721202,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:696",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585720288,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586154085,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:540",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153168,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586404531,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:543",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403520,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586546128,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:537",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586546128,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794464,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:552",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794464,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586940800,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586940800,
      "name": "phy_start_aneg",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587755792,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:677",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587755792,
      "name": "phy_start_aneg",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587815360,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:762",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587815360,
      "name": "phy_start_aneg",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587694576,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:763",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587694576,
      "name": "phy_start_aneg",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290442,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:742",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286144,
      "name": "phy_start_aneg",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674621,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:747",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669360,
      "name": "phy_start_aneg",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591286381,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:776",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591282064,
      "name": "phy_start_aneg",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591641935,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:981",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591637536,
      "name": "phy_start_aneg",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592379383,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:1036",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mii_ioctl"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592378128,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499924256,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499924256,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232469108,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232469108,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293240256,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293240256,
      "name": "phy_start_aneg",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277011354,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277011354,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586697808,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586697808,
      "name": "phy_start_aneg",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586566160,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586566160,
      "name": "phy_start_aneg",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586895360,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586895360,
      "name": "phy_start_aneg",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int phy_start_aneg(struct phy_device * phydev)
```

```json
{
  "name": "phy_start_aneg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587001744,
      "name": "phy_start_aneg",
      "external": true,
      "loc": "drivers/net/phy/phy.c:563",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_mii_ioctl",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_ethtool_sset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587001744,
      "name": "phy_start_aneg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
