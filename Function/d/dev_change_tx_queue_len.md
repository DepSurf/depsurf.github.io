# Function: <code>dev_change_tx_queue_len</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587851504,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:7140",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587851504,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587992016,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:7732",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587992016,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:7742",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312625,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588303744,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588518936,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588510272,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8454",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589392824,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589381504,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8699",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630083,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589387328,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8958",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591573480,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071589284176,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8948",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592699669,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071590011520,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8713",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:tx_queue_len_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594585831,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591550288,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593324736,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8700",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:tx_queue_len_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593324736,
      "name": "dev_change_tx_queue_len",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593786608,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8706",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:tx_queue_len_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593786608,
      "name": "dev_change_tx_queue_len",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594567248,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8824",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc",
        "net/core/net-sysfs.c:tx_queue_len_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594567248,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502043760,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502043760,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234795556,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234795556,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295491616,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295491616,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278330304,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278330304,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125672,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588117008,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838504,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071587829840,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457496,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588448832,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```

```json
{
  "name": "dev_change_tx_queue_len",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dev_change_tx_queue_len",
      "external": true,
      "loc": "net/core/dev.c:8041",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/dev_ioctl.c:dev_ifsioc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588594408,
      "name": "dev_change_tx_queue_len.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588585744,
      "name": "dev_change_tx_queue_len",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int dev_change_tx_queue_len(struct net_device * dev, long unsigned int new_len)
```
</details>
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
