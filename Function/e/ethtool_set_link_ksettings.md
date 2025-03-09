# Function: <code>ethtool_set_link_ksettings</code>

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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586750719,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:710",
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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586937567,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:721",
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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587063036,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:724",
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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587564485,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:738",
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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587873003,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:711",
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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588019994,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316256,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:663",
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
      "addr": 18446744071588316256,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522912,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446744071588522912,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589857648,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:562",
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
      "addr": 18446744071589857648,
      "name": "ethtool_set_link_ksettings",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589898720,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:566",
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
      "addr": 18446744071589898720,
      "name": "ethtool_set_link_ksettings",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589805664,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:566",
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
      "addr": 18446744071589805664,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:568",
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
      "addr": 18446744071590567392,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071592711690,
      "name": "ethtool_set_link_ksettings.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:592",
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
      "addr": 18446744071592183680,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071594597745,
      "name": "ethtool_set_link_ksettings.cold",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:573",
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
      "addr": 18446744071594010960,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071596333708,
      "name": "ethtool_set_link_ksettings.cold",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:574",
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
      "addr": 18446744071594388688,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071596862674,
      "name": "ethtool_set_link_ksettings.cold",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/ethtool/ioctl.c:577",
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
      "addr": 18446744071595189728,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071597787723,
      "name": "ethtool_set_link_ksettings.cold",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502058608,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446603336502058608,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234824552,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295506144,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 13835058055295506144,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278340268,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446743936278340268,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588129648,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446744071588129648,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587842480,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446744071587842480,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588461472,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446744071588461472,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
```

```json
{
  "name": "ethtool_set_link_ksettings",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588598384,
      "name": "ethtool_set_link_ksettings",
      "external": false,
      "loc": "net/core/ethtool.c:664",
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
      "addr": 18446744071588598384,
      "name": "ethtool_set_link_ksettings",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
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
int ethtool_set_link_ksettings(struct net_device * dev, void * useraddr)
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
