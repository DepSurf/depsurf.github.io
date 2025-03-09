# Function: <code>ncsi_unregister_netlink</code>

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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589114896,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:411",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589114896,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589348560,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:779",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589348560,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589804527,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589803792,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590027490,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590027008,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591060523,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591059888,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503778328,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503778328,
      "name": "ncsi_unregister_netlink",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236398948,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236398948,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297620000,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297620000,
      "name": "ncsi_unregister_netlink",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279688138,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279688138,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589631090,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589630608,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589355618,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589355136,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590073122,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590072640,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ncsi_unregister_netlink(struct net_device * dev)
```

```json
{
  "name": "ncsi_unregister_netlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ncsi_unregister_netlink",
      "external": true,
      "loc": "net/ncsi/ncsi-netlink.c:780",
      "file": "net/ncsi/ncsi-netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-manage.c:ncsi_unregister_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590123202,
      "name": "ncsi_unregister_netlink.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590122720,
      "name": "ncsi_unregister_netlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int ncsi_unregister_netlink(struct net_device * dev)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int ncsi_unregister_netlink(struct net_device * dev)
```
</details>
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
