# Function: <code>netdev_change_owner</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703232,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703232,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589569328,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1906",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589569328,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589578944,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1957",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589578944,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589476048,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1973",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589476048,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590214880,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:2031",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590214880,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591791200,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:2033",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591791200,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593584960,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:2033",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593584960,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594057088,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:2061",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594057088,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 481
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594847568,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:2073",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594847568,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502264704,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502264704,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235006604,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235006604,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295760128,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295760128,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278501110,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278501110,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588309968,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309968,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588022752,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022752,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588641792,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588641792,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```

```json
{
  "name": "netdev_change_owner",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781280,
      "name": "netdev_change_owner",
      "external": true,
      "loc": "net/core/net-sysfs.c:1875",
      "file": "net/core/net-sysfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:dev_change_net_namespace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781280,
      "name": "netdev_change_owner",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int netdev_change_owner(struct net_device * ndev, const struct net * net_old, const struct net * net_new)
```
</details>
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
