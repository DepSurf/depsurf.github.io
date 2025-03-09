# Function: <code>ethtool_get_link_ksettings</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586750969,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:646",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586937710,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:657",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587063167,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:660",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587564622,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:674",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587878584,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:647",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588012398,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588318864,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:609",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588318864,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588525520,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588525520,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589858592,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:506",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589858592,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589899664,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:510",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589899664,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806272,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:510",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806272,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:512",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590568624,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    },
    {
      "addr": 18446744071592711710,
      "name": "ethtool_get_link_ksettings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:536",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592184960,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
    },
    {
      "addr": 18446744071594597766,
      "name": "ethtool_get_link_ksettings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:516",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594012816,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
    },
    {
      "addr": 18446744071596333729,
      "name": "ethtool_get_link_ksettings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:517",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594389376,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
    },
    {
      "addr": 18446744071596862695,
      "name": "ethtool_get_link_ksettings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:520",
      "file": "net/ethtool/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ethtool/ioctl.c:__dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595190416,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
    },
    {
      "addr": 18446744071597787744,
      "name": "ethtool_get_link_ksettings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502060832,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502060832,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234823528,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295507440,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295507440,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278342796,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278342796,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588132256,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588132256,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845088,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845088,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588464080,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588464080,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_get_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588600992,
      "name": "ethtool_get_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:610",
      "file": "net/core/ethtool.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/ethtool.c:dev_ethtool"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588600992,
      "name": "ethtool_get_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int ethtool_get_link_ksettings(struct net_device * dev, void * useraddr)
```
</details>
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
