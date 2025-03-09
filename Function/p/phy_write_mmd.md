# Function: <code>phy_write_mmd</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585725104,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:72",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy_device.c:genphy_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725104,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586158368,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:252",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy_device.c:genphy_config_aneg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586158368,
      "name": "phy_write_mmd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586409744,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:296",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409744,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586553520,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:467",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553520,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 232
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586804096,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:432",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586804096,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586950192,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586950192,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587764576,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:514",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587764576,
      "name": "phy_write_mmd",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587823760,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:561",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823760,
      "name": "phy_write_mmd",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703184,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:561",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703184,
      "name": "phy_write_mmd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588294816,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:562",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588294816,
      "name": "phy_write_mmd",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589682048,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:557",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682048,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591294576,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:640",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294576,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591653216,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:643",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591653216,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592397152,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:641",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592397152,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499934544,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499934544,
      "name": "phy_write_mmd",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232478200,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232478200,
      "name": "phy_write_mmd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293254080,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293254080,
      "name": "phy_write_mmd",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277019828,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277019828,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586707200,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707200,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586575520,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586575520,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586904752,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904752,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```

```json
{
  "name": "phy_write_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587011136,
      "name": "phy_write_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:471",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587011136,
      "name": "phy_write_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int phy_write_mmd(struct phy_device * phydev, int devad, u32 regnum, u16 val)
```
</details>
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
