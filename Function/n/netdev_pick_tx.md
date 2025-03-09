# Function: <code>netdev_pick_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, void * accel_priv)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586303072,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3022",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586303072,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, void * accel_priv)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586730992,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3265",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586730992,
      "name": "netdev_pick_tx",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, void * accel_priv)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586916864,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3269",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586916864,
      "name": "netdev_pick_tx",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, void * accel_priv)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037696,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3349",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netif_receive_skb_internal",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037696,
      "name": "netdev_pick_tx",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, void * accel_priv)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587535712,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3395",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587535712,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, void * accel_priv)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3438",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587860598,
      "name": "netdev_pick_tx.cold.162",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587839360,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct netdev_queue * netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3733",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:generic_xdp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/xfrm/xfrm_device.c:xfrm_dev_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001048,
      "name": "netdev_pick_tx.cold.169",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587972992,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257168,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3717",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588257168,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588462320,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588462320,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589328064,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3975",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_pick_tx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328064,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 563
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327376,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4006",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_pick_tx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327376,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 590
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589222880,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4089",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222880,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4054",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695624,
      "name": "netdev_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    },
    {
      "addr": 18446744071589944976,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4086",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581291,
      "name": "netdev_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446744071591479456,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 935
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4073",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323038,
      "name": "netdev_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071593248512,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 964
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4033",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/net_failover.c:net_failover_select_queue",
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596853134,
      "name": "netdev_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071593709328,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:4183",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/net_failover.c:net_failover_select_queue",
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597778104,
      "name": "netdev_pick_tx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071594488400,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 871
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501986784,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501986784,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234741892,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234741892,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295419952,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295419952,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 816
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278284996,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278284996,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588069104,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588069104,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587782192,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782192,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588400880,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400880,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
u16 netdev_pick_tx(struct net_device * dev, struct sk_buff * skb, struct net_device * sb_dev)
```

```json
{
  "name": "netdev_pick_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588537280,
      "name": "netdev_pick_tx",
      "external": true,
      "loc": "net/core/dev.c:3617",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_core_pick_tx",
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588537280,
      "name": "netdev_pick_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device * sb_dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void * accel_priv</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct netdev_queue *</code> ➡️ <code>u16</code>
</li>
</ul>
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
