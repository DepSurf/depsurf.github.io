# Function: <code>phy_queue_state_machine</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586544837,
      "name": "phy_queue_state_machine",
      "external": false,
      "loc": "drivers/net/phy/phy.c:474",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586792421,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:489",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586792320,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586938645,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586938544,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587754149,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:469",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587753504,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587819666,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:469",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812656,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587699154,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:469",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692144,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290514,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:417",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283824,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589668485,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:422",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667424,
      "name": "phy_queue_state_machine",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591279749,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:451",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277904,
      "name": "phy_queue_state_machine",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591636213,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:464",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632944,
      "name": "phy_queue_state_machine",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592377544,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:518",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592373536,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499922584,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499922496,
      "name": "phy_queue_state_machine",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232467116,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232467044,
      "name": "phy_queue_state_machine",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293237900,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293237712,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277009176,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277009092,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586695653,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695552,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586563989,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586563888,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586893205,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586893104,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
```

```json
{
  "name": "phy_queue_state_machine",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586999589,
      "name": "phy_queue_state_machine",
      "external": true,
      "loc": "drivers/net/phy/phy.c:494",
      "file": "drivers/net/phy/phy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586999488,
      "name": "phy_queue_state_machine",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void phy_queue_state_machine(struct phy_device * phydev, long unsigned int jiffies)
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
