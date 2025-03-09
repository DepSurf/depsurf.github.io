# Function: <code>mctp_dev_get_rtnl</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct mctp_dev * mctp_dev_get_rtnl(const struct net_device * dev)
```

```json
{
  "name": "mctp_dev_get_rtnl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593757177,
      "name": "mctp_dev_get_rtnl",
      "external": true,
      "loc": "net/mctp/device.c:47",
      "file": "net/mctp/device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_dev_notify",
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_fill_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": [
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593756288,
      "name": "mctp_dev_get_rtnl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct mctp_dev * mctp_dev_get_rtnl(const struct net_device * dev)
```

```json
{
  "name": "mctp_dev_get_rtnl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595692195,
      "name": "mctp_dev_get_rtnl",
      "external": true,
      "loc": "net/mctp/device.c:47",
      "file": "net/mctp/device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_fill_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": [
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595694368,
      "name": "mctp_dev_get_rtnl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct mctp_dev * mctp_dev_get_rtnl(const struct net_device * dev)
```

```json
{
  "name": "mctp_dev_get_rtnl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596203619,
      "name": "mctp_dev_get_rtnl",
      "external": true,
      "loc": "net/mctp/device.c:47",
      "file": "net/mctp/device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_fill_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": [
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596205840,
      "name": "mctp_dev_get_rtnl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct mctp_dev * mctp_dev_get_rtnl(const struct net_device * dev)
```

```json
{
  "name": "mctp_dev_get_rtnl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597081382,
      "name": "mctp_dev_get_rtnl",
      "external": true,
      "loc": "net/mctp/device.c:47",
      "file": "net/mctp/device.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/mctp/device.c:mctp_set_link_af",
        "net/mctp/device.c:mctp_fill_link_af",
        "net/mctp/device.c:mctp_rtm_deladdr",
        "net/mctp/device.c:mctp_rtm_newaddr"
      ],
      "caller_func": [
        "net/mctp/neigh.c:mctp_rtm_delneigh",
        "net/mctp/neigh.c:mctp_rtm_newneigh"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597083648,
      "name": "mctp_dev_get_rtnl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
struct mctp_dev * mctp_dev_get_rtnl(const struct net_device * dev)
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
