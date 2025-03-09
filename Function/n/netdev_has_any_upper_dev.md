# Function: <code>netdev_has_any_upper_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586277220,
      "name": "netdev_has_any_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:4947",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586703258,
      "name": "netdev_has_any_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:5291",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586889766,
      "name": "netdev_has_any_upper_dev",
      "external": false,
      "loc": "net/core/dev.c:5466",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:rollback_registered_many"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587004352,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:5671",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587004352,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587502944,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:5812",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587502944,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807216,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:5942",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807216,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943280,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6517",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943280,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588252784,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6527",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252784,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458000,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458000,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325472,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6861",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325472,
      "name": "netdev_has_any_upper_dev",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589324592,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:7018",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324592,
      "name": "netdev_has_any_upper_dev",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589220256,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:7277",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220256,
      "name": "netdev_has_any_upper_dev",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:7267",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695820,
      "name": "netdev_has_any_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071589949056,
      "name": "netdev_has_any_upper_dev",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6788",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581497,
      "name": "netdev_has_any_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591484624,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6774",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323195,
      "name": "netdev_has_any_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593253712,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6779",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596853284,
      "name": "netdev_has_any_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593714592,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6897",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:unregister_netdevice_many_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597778275,
      "name": "netdev_has_any_upper_dev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594494144,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501983032,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501983032,
      "name": "netdev_has_any_upper_dev",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234737176,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234737176,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295413408,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295413408,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278281326,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278281326,
      "name": "netdev_has_any_upper_dev",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588064784,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588064784,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587777872,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777872,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588396560,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396560,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
```

```json
{
  "name": "netdev_has_any_upper_dev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588532976,
      "name": "netdev_has_any_upper_dev",
      "external": true,
      "loc": "net/core/dev.c:6470",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:rollback_registered_many",
        "net/core/dev.c:rollback_registered_many"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588532976,
      "name": "netdev_has_any_upper_dev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
bool netdev_has_any_upper_dev(struct net_device * dev)
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
