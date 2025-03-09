# Function: <code>__skb_get_hash_symmetric</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
u32 __skb_get_hash_symmetric(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586685744,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:656",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586685744,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586871520,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:761",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871520,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586995984,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:956",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586995984,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587494672,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1155",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587494672,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587798416,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1210",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587798416,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587933392,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1386",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587933392,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588243056,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1499",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243056,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447856,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447856,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589316768,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1555",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589316768,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589315808,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1578",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315808,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211488,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1604",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211488,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589933504,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1609",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589933504,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591465792,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1663",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591465792,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 554
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593234640,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1735",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593234640,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 525
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593694944,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1775",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593694944,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594473296,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1826",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594473296,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 580
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501971136,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501971136,
      "name": "__skb_get_hash_symmetric",
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234725624,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_xdp_one",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234725624,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295397584,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295397584,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 732
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278271042,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278271042,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588054640,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588054640,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587767728,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587767728,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588386416,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588386416,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
u32 __skb_get_hash_symmetric(const struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash_symmetric",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522160,
      "name": "__skb_get_hash_symmetric",
      "external": true,
      "loc": "net/core/flow_dissector.c:1536",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_sendmsg",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522160,
      "name": "__skb_get_hash_symmetric",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
u32 __skb_get_hash_symmetric(struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff * skb</code> ➡️ <code>const struct sk_buff * skb</code>
</li>
</ul>
</details>
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
