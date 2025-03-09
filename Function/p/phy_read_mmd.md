# Function: <code>phy_read_mmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585055181,
      "name": "phy_read_mmd",
      "external": false,
      "loc": "include/linux/phy.h:617",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:gen10g_read_status"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585438848,
      "name": "phy_read_mmd",
      "external": false,
      "loc": "include/linux/phy.h:614",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:gen10g_read_status"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585640848,
      "name": "phy_read_mmd",
      "external": false,
      "loc": "include/linux/phy.h:649",
      "file": "drivers/net/phy/phy_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy_device.c:gen10g_read_status",
        "drivers/net/phy/phy_device.c:gen10g_read_status"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585724912,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:34",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
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
      "addr": 18446744071585724912,
      "name": "phy_read_mmd",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586158160,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:214",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
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
      "addr": 18446744071586158160,
      "name": "phy_read_mmd",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586409520,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:258",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409520,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586553296,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:429",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_disable_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553296,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586803424,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:371",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586803424,
      "name": "phy_read_mmd",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586949520,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949520,
      "name": "phy_read_mmd",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587766432,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:455",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_wait_init",
        "drivers/net/phy/bcm84881.c:bcm84881_wait_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587766432,
      "name": "phy_read_mmd",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825616,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:502",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_wait_init",
        "drivers/net/phy/bcm84881.c:bcm84881_wait_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825616,
      "name": "phy_read_mmd",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587705040,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:502",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_resume",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587705040,
      "name": "phy_read_mmd",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588296864,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:503",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_resume",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588296864,
      "name": "phy_read_mmd",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589683872,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:498",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_mdix",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_resume",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683872,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591296816,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:581",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_mdix",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_resume",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296816,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591655296,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:584",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_mdix",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_resume",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591655296,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592396432,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:596",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_plca_get_cfg",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_baset1_read_status",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_ext_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_baset1_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_eee_adv",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_mdix",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_resume",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_read_status",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done",
        "drivers/net/phy/bcm84881.c:bcm84881_aneg_done"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592396432,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499933688,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499933688,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232477556,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232477556,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293253088,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293253088,
      "name": "phy_read_mmd",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277019090,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277019090,
      "name": "phy_read_mmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586706528,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586706528,
      "name": "phy_read_mmd",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586574848,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586574848,
      "name": "phy_read_mmd",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586904080,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586904080,
      "name": "phy_read_mmd",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
```

```json
{
  "name": "phy_read_mmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587010464,
      "name": "phy_read_mmd",
      "external": true,
      "loc": "drivers/net/phy/phy-core.c:410",
      "file": "drivers/net/phy/phy-core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_set_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_ethtool_get_eee",
        "drivers/net/phy/phy.c:phy_get_eee_err",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy.c:phy_init_eee",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_read_abilities",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_pma",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_lpa",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_read_link",
        "drivers/net/phy/phy-c45.c:genphy_c45_aneg_done",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced",
        "drivers/net/phy/phy-c45.c:genphy_c45_pma_setup_forced"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587010464,
      "name": "phy_read_mmd",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int phy_read_mmd(struct phy_device * phydev, int devad, u32 regnum)
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
