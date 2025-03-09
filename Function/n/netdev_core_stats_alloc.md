# Function: <code>netdev_core_stats_alloc</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device_core_stats * netdev_core_stats_alloc(struct net_device * dev)
```

```json
{
  "name": "netdev_core_stats_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591483840,
      "name": "netdev_core_stats_alloc",
      "external": true,
      "loc": "net/core/dev.c:10400",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591483840,
      "name": "netdev_core_stats_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct net_device_core_stats * netdev_core_stats_alloc(struct net_device * dev)
```

```json
{
  "name": "netdev_core_stats_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593252240,
      "name": "netdev_core_stats_alloc",
      "external": true,
      "loc": "net/core/dev.c:10379",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/tun.c:tun_net_xmit",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593252240,
      "name": "netdev_core_stats_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct net_device_core_stats * netdev_core_stats_alloc(struct net_device * dev)
```

```json
{
  "name": "netdev_core_stats_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593713088,
      "name": "netdev_core_stats_alloc",
      "external": true,
      "loc": "net/core/dev.c:10391",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_xdp_act",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/net_failover.c:net_failover_start_xmit",
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb",
        "net/core/dev.c:__dev_forward_skb2",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/gro_cells.c:gro_cells_receive",
        "net/ipv4/ip_input.c:ip_rcv_core",
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm",
        "net/ipv6/ip6_input.c:ip6_rcv_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593713088,
      "name": "netdev_core_stats_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "netdev_core_stats_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594492233,
      "name": "netdev_core_stats_alloc",
      "external": false,
      "loc": "net/core/dev.c:10584",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:netdev_core_stats_inc"
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
struct net_device_core_stats * netdev_core_stats_alloc(struct net_device * dev)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct net_device_core_stats * netdev_core_stats_alloc(struct net_device * dev)
```
</details>
</li>
</ul>
