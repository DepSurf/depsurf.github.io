# Function: <code>__skb_get_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586260640,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:674",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__skb_tx_hash",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:enqueue_to_backlog",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:packet_rcv_fanout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586260640,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 763
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586684976,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:680",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__skb_tx_hash",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586684976,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 753
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586870736,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:785",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_get_user",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/tun.c:tun_select_queue",
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__skb_tx_hash",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586870736,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 769
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586995216,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:980",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__skb_tx_hash",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586995216,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587493888,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1179",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__skb_tx_hash",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587493888,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 774
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587799120,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1234",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587799120,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 736
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587934080,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1410",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:__netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934080,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 712
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588243712,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1523",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243712,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 681
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588448288,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448288,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589316976,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1579",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:skb_flow_limit",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589316976,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589316016,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1602",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:skb_flow_limit",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block",
        "net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state",
        "net/mptcp/syncookies.c:subflow_init_req_cookie_join_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589316016,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211696,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1628",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211696,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589934000,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1633",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589934000,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591466352,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1687",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591466352,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 614
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593235184,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1759",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593235184,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593695552,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1799",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593695552,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594473904,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1849",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594473904,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501971640,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501971640,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234726112,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_fill_curr_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234726112,
      "name": "__skb_get_hash",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295398320,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295398320,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278271458,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover",
        "net/packet/af_packet.c:prb_run_all_ft_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278271458,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588055072,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055072,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587768160,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/vxlan.c:vxlan_fill_metadata_dst",
        "drivers/net/vxlan.c:vxlan_xmit_one",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv4/ip_tunnel.c:ip_tunnel_xmit",
        "net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587768160,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588386848,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588386848,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void __skb_get_hash(struct sk_buff * skb)
```

```json
{
  "name": "__skb_get_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522592,
      "name": "__skb_get_hash",
      "external": true,
      "loc": "net/core/flow_dissector.c:1560",
      "file": "net/core/flow_dissector.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_select_queue",
        "net/core/dev.c:enqueue_to_backlog",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:get_rps_cpu",
        "net/core/dev.c:netdev_pick_tx",
        "net/core/dev.c:__get_xps_queue_idx",
        "net/core/filter.c:bpf_get_hash_recalc",
        "net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap",
        "net/packet/af_packet.c:fanout_demux_rollover"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522592,
      "name": "__skb_get_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
