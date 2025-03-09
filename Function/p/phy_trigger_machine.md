# Function: <code>phy_trigger_machine</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void phy_trigger_machine(struct phy_device * phydev, bool sync)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585635152,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:659",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585635152,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void phy_trigger_machine(struct phy_device * phydev, bool sync)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585719888,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:727",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585719888,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void phy_trigger_machine(struct phy_device * phydev, bool sync)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152704,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:572",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152704,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void phy_trigger_machine(struct phy_device * phydev, bool sync)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586403024,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:575",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_aneg_priv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586403024,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586544837,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:481",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586792421,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:496",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586938645,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587754149,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:476",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587814200,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:481",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812704,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587693688,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:481",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692192,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290514,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:429",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283872,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589668485,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:434",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667488,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591279749,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:463",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277984,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591636213,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:476",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591633024,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void phy_trigger_machine(struct phy_device * phydev)
```

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592377544,
      "name": "phy_trigger_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:530",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": [
        "drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592373616,
      "name": "phy_trigger_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499922584,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232467116,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293237900,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277009176,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586695653,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586563989,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586893205,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_trigger_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586999589,
      "name": "phy_trigger_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:501",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void phy_trigger_machine(struct phy_device * phydev, bool sync)
```
</details>
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
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
void phy_trigger_machine(struct phy_device * phydev, bool sync)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void phy_trigger_machine(struct phy_device * phydev)
```
</details>
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
