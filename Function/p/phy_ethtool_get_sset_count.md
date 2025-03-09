# Function: <code>phy_ethtool_get_sset_count</code>

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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587879576,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1083",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588021062,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1106",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588334244,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1198",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588540851,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589862232,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1483",
      "file": "net/ethtool/ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ethtool/ioctl.c:ethtool_get_phy_stats",
        "net/ethtool/ioctl.c:__ethtool_get_sset_count"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589888999,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1483",
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
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587812848,
      "name": "phy_ethtool_get_sset_count",
      "external": true,
      "loc": "drivers/net/phy/phy.c:522",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587812848,
      "name": "phy_ethtool_get_sset_count",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587692336,
      "name": "phy_ethtool_get_sset_count",
      "external": true,
      "loc": "drivers/net/phy/phy.c:522",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587692336,
      "name": "phy_ethtool_get_sset_count",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588283568,
      "name": "phy_ethtool_get_sset_count",
      "external": true,
      "loc": "drivers/net/phy/phy.c:470",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588283568,
      "name": "phy_ethtool_get_sset_count",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667152,
      "name": "phy_ethtool_get_sset_count",
      "external": true,
      "loc": "drivers/net/phy/phy.c:475",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667152,
      "name": "phy_ethtool_get_sset_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591277520,
      "name": "phy_ethtool_get_sset_count",
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
      "addr": 18446744071591277520,
      "name": "phy_ethtool_get_sset_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591632352,
      "name": "phy_ethtool_get_sset_count",
      "external": true,
      "loc": "drivers/net/phy/phy.c:517",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591632352,
      "name": "phy_ethtool_get_sset_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int phy_ethtool_get_sset_count(struct phy_device * phydev)
```

```json
{
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592372944,
      "name": "phy_ethtool_get_sset_count",
      "external": true,
      "loc": "drivers/net/phy/phy.c:571",
      "file": "drivers/net/phy/phy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592372944,
      "name": "phy_ethtool_get_sset_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502076172,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234827728,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295527700,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278352804,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588147587,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587860419,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588479411,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
  "name": "phy_ethtool_get_sset_count",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588616323,
      "name": "phy_ethtool_get_sset_count",
      "external": false,
      "loc": "include/linux/phy.h:1213",
      "file": "net/core/ethtool.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/ethtool.c:dev_ethtool",
        "net/core/ethtool.c:__ethtool_get_sset_count"
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
int phy_ethtool_get_sset_count(struct phy_device * phydev)
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
