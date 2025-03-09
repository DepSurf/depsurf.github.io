# Function: <code>netdev_offload_xstats_get</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int netdev_offload_xstats_get(struct net_device * dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 * p_stats, bool * p_used, struct netlink_ext_ack * extack)
```

```json
{
  "name": "netdev_offload_xstats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_offload_xstats_get",
      "external": true,
      "loc": "net/core/dev.c:8081",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581684,
      "name": "netdev_offload_xstats_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071591486752,
      "name": "netdev_offload_xstats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int netdev_offload_xstats_get(struct net_device * dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 * p_stats, bool * p_used, struct netlink_ext_ack * extack)
```

```json
{
  "name": "netdev_offload_xstats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_offload_xstats_get",
      "external": true,
      "loc": "net/core/dev.c:8067",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323382,
      "name": "netdev_offload_xstats_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071593256400,
      "name": "netdev_offload_xstats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int netdev_offload_xstats_get(struct net_device * dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 * p_stats, bool * p_used, struct netlink_ext_ack * extack)
```

```json
{
  "name": "netdev_offload_xstats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_offload_xstats_get",
      "external": true,
      "loc": "net/core/dev.c:8072",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596854552,
      "name": "netdev_offload_xstats_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071593761776,
      "name": "netdev_offload_xstats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
int netdev_offload_xstats_get(struct net_device * dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 * p_stats, bool * p_used, struct netlink_ext_ack * extack)
```

```json
{
  "name": "netdev_offload_xstats_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_offload_xstats_get",
      "external": true,
      "loc": "net/core/dev.c:8190",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill",
        "net/core/rtnetlink.c:rtnl_offload_xstats_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597779543,
      "name": "netdev_offload_xstats_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071594540768,
      "name": "netdev_offload_xstats_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int netdev_offload_xstats_get(struct net_device * dev, enum netdev_offload_xstats_type type, struct rtnl_hw_stats64 * p_stats, bool * p_used, struct netlink_ext_ack * extack)
```
</details>
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
