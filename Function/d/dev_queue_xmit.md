# Function: <code>dev_queue_xmit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304720,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3184",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/neighbour.c:neigh_xmit",
        "net/core/filter.c:bpf_clone_redirect",
        "net/core/filter.c:skb_do_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304720,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586732960,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3436",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:skb_do_redirect",
        "net/core/filter.c:bpf_clone_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586732960,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586918752,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3430",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586918752,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587039584,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3511",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587039584,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587537936,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3557",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587537936,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587841840,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3600",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841840,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587981676,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3895",
      "file": "net/core/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/dev.c:__netif_receive_skb_core"
      ],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975488,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588289328,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3904",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588289328,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588494704,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588494704,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589365648,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:4162",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/netlink/af_netlink.c:__netlink_deliver_tap_skb",
        "net/ipv4/ip_output.c:neigh_hh_output",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:neigh_hh_output",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589365648,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589371216,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:4194",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:neigh_hh_output",
        "net/netlink/af_netlink.c:__netlink_deliver_tap_skb",
        "net/ipv4/ip_output.c:neigh_hh_output",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:neigh_hh_output",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371216,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589267168,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:4277",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:neigh_hh_output",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:neigh_hh_output",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:neigh_hh_output",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589267168,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589993280,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:4245",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:bpf_out_neigh_v6",
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/netlink/af_netlink.c:__netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993280,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591599085,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591727774,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592127866,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592316382,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592614551,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593029774,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593430978,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593490917,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593583978,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/ncsi/ncsi-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593758233,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3006",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_route_output"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593461872,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593380141,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593516173,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593950919,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594153758,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594479170,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594922030,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595345650,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595409408,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg_spkt"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595510150,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/ncsi/ncsi-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595696297,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3031",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_route_output"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595379280,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591883445,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "drivers/net/net_failover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/net_failover.c:net_failover_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593842299,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593980426,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594327327,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594541086,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594870786,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595313726,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595741154,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595807541,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596018838,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/ncsi/ncsi-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596207760,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3086",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_route_output"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592622981,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "drivers/net/net_failover.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/net_failover.c:net_failover_start_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594623960,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594764362,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:__bpf_redirect",
        "net/core/filter.c:__bpf_redirect_no_mac",
        "net/core/filter.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595127007,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/netlink/af_netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:__netlink_deliver_tap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595343982,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/ipv4/ip_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595682146,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/ipv4/arp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/arp.c:arp_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596155102,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/ipv6/ip6_output.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_output.c:neigh_hh_output"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596588994,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/ipv6/seg6_local.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/seg6_local.c:input_action_end_dx2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596658105,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/packet/af_packet.c:packet_xmit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596882867,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/ncsi/ncsi-cmd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597085494,
      "name": "dev_queue_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3167",
      "file": "net/mctp/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/route.c:mctp_route_output"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502026208,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502026208,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234778104,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234778104,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295468960,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295468960,
      "name": "dev_queue_xmit",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278316428,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278316428,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588101488,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588101488,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587814400,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587814400,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588433264,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433264,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
int dev_queue_xmit(struct sk_buff * skb)
```

```json
{
  "name": "dev_queue_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569632,
      "name": "dev_queue_xmit",
      "external": true,
      "loc": "net/core/dev.c:3804",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/neighbour.c:neigh_xmit",
        "net/core/neighbour.c:neigh_direct_output",
        "net/core/neighbour.c:neigh_connected_output",
        "net/core/filter.c:__bpf_redirect",
        "net/netlink/af_netlink.c:netlink_deliver_tap",
        "net/ipv4/ip_output.c:ip_finish_output2",
        "net/ipv4/arp.c:arp_xmit",
        "net/ipv6/ip6_output.c:ip6_finish_output2",
        "net/ipv6/seg6_local.c:input_action_end_dx2",
        "net/packet/af_packet.c:packet_sendmsg_spkt",
        "net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569632,
      "name": "dev_queue_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int dev_queue_xmit(struct sk_buff * skb)
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
