# Function: <code>__kfree_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209776,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:681",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:kfree_skb",
        "net/core/skbuff.c:consume_skb"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_free_datagram_locked",
        "net/core/dev.c:net_tx_action",
        "net/core/dev.c:napi_gro_receive",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209776,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586637108,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:682",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_collapse",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586635872,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586822644,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:682",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586821280,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586961588,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:679",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952384,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587445972,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:639",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444048,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587748336,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:639",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587748336,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587882432,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:643",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587882432,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588189540,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187696,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588394692,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392848,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589254500,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:676",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/mptcp/protocol.c:__mptcp_recvmsg_mskq",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255840,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589253683,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:690",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/mptcp/protocol.c:__mptcp_recvmsg_mskq",
        "net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:mptcp_subflow_discard_data",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589255008,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589148167,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:738",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155520,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589868388,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:754",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589875792,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591427475,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:754",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free"
      ],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/gro.c:napi_gro_receive",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591407696,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593193763,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:928",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:kfree_skb_reason"
      ],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/gro.c:napi_gro_receive",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593172352,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593653008,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:1020",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/gro.c:napi_gro_receive",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593626368,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594428784,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:1106",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:skb_attempt_defer_free",
        "net/core/skbuff.c:kfree_skb_list_reason",
        "net/core/skbuff.c:kfree_skb_reason"
      ],
      "caller_func": [
        "net/core/dev.c:net_tx_action",
        "net/core/gro.c:napi_gro_receive",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/mptcp/protocol.c:mptcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag",
        "net/mptcp/protocol.c:__mptcp_ofo_queue",
        "net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow",
        "net/mptcp/protocol.c:__mptcp_move_skb",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/protocol.c:mptcp_data_queue_ofo",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:get_mapping_status",
        "net/mptcp/subflow.c:validate_data_csum"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594401680,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501910472,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501908320,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234671572,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234669624,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295324164,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295321072,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278223574,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_validate_incoming",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_data_queue_ofo",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278221818,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588001476,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587999632,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587714564,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712720,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588333252,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588331408,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __kfree_skb(struct sk_buff * skb)
```

```json
{
  "name": "__kfree_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588468728,
      "name": "__kfree_skb",
      "external": true,
      "loc": "net/core/skbuff.c:677",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/skbuff.c:consume_skb",
        "net/core/skbuff.c:kfree_skb"
      ],
      "caller_func": [
        "net/core/dev.c:napi_gro_receive",
        "net/core/dev.c:net_tx_action",
        "net/core/netpoll.c:zap_completion_queue",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recv_skb",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_collapse_one",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_send_rcvq",
        "net/ipv4/tcp_input.c:tcp_drop",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/xfrm6_input.c:xfrm6_transport_finish2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466864,
      "name": "__kfree_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
