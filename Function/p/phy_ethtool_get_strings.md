# Function: <code>phy_ethtool_get_strings</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587880360,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1071",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588021795,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1094",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588335038,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1186",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588541669,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589860184,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1471",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:__ethtool_get_strings"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589889391,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1471",
      "file": "net/ethtool/strset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/strset.c:strset_prepare_data"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587812752,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:504",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812752,
      "name": "phy_ethtool_get_strings",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587692240,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:504",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692240,
      "name": "phy_ethtool_get_strings",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588283472,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:452",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283472,
      "name": "phy_ethtool_get_strings",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667040,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:457",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667040,
      "name": "phy_ethtool_get_strings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591277392,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:486",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591277392,
      "name": "phy_ethtool_get_strings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591632224,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:499",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632224,
      "name": "phy_ethtool_get_strings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
```

```json
{
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592372816,
      "name": "phy_ethtool_get_strings",
      "external": true,
      "loc": "drivers/net/phy/phy.c:553",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592372816,
      "name": "phy_ethtool_get_strings",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502077424,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234828612,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295528320,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278353208,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588148405,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587861237,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588480229,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
  "name": "phy_ethtool_get_strings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588617141,
      "name": "phy_ethtool_get_strings",
      "external": false,
      "loc": "include/linux/phy.h:1201",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int phy_ethtool_get_strings(struct phy_device * phydev, u8 * data)
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
