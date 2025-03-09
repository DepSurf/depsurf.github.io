# Function: <code>dev_core_stats_tx_dropped_inc</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_core_stats_tx_dropped_inc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589726795,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:3924",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591535332,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:3924",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592977754,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:3924",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void dev_core_stats_tx_dropped_inc(struct net_device * dev)
```

```json
{
  "name": "dev_core_stats_tx_dropped_inc",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591350317,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:3968",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593309060,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:3968",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594865093,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:3968",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594861408,
      "name": "dev_core_stats_tx_dropped_inc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void dev_core_stats_tx_dropped_inc(struct net_device * dev)
```

```json
{
  "name": "dev_core_stats_tx_dropped_inc",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591712050,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4027",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591883465,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4027",
      "file": "drivers/net/net_failover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/net_failover.c:net_failover_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593770772,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4027",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595256820,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4027",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ],
      "caller_func": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595252864,
      "name": "dev_core_stats_tx_dropped_inc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
  "name": "dev_core_stats_tx_dropped_inc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592366879,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4093",
      "file": "drivers/net/netkit.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/netkit.c:netkit_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592455787,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4093",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_net_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592623001,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4093",
      "file": "drivers/net/net_failover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/net_failover.c:net_failover_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594550356,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4093",
      "file": "net/core/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_direct_xmit",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/dev.c:validate_xmit_skb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596097252,
      "name": "dev_core_stats_tx_dropped_inc",
      "external": false,
      "loc": "include/linux/netdevice.h:4093",
      "file": "net/xfrm/xfrm_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_device.c:validate_xmit_xfrm"
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void dev_core_stats_tx_dropped_inc(struct net_device * dev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void dev_core_stats_tx_dropped_inc(struct net_device * dev)
```
</details>
</li>
</ul>
