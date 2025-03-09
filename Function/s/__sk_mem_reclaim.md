# Function: <code>__sk_mem_reclaim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586195568,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2150",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/datagram.c:skb_free_datagram_locked",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/datagram.c:skb_kill_datagram",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/af_inet.c:inet_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586195568,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586618080,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2211",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc",
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/core/datagram.c:skb_free_datagram",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/udp.c:first_packet_length",
        "net/ipv4/af_inet.c:inet_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618080,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586802587,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2242",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/core/datagram.c:skb_free_datagram",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/af_inet.c:inet_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802400,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586926491,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2401",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock",
        "net/ipv4/af_inet.c:inet_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586926288,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587419086,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2441",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587418880,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587721646,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2522",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg",
        "kernel/bpf/sockmap.c:bpf_exec_tx_verdict",
        "kernel/bpf/sockmap.c:free_sg",
        "kernel/bpf/sockmap.c:free_bytes_sg",
        "kernel/bpf/sockmap.c:free_bytes_sg",
        "kernel/bpf/sockmap.c:bpf_tcp_push",
        "kernel/bpf/sockmap.c:bpf_tcp_push",
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587721440,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587854670,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2466",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854464,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588159067,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2609",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588158864,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588364331,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364128,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589223435,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2732",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_queue",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clear_xmit",
        "net/mptcp/protocol.c:mptcp_clean_una",
        "net/mptcp/protocol.c:mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223344,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589222107,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2724",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_queue",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clear_xmit",
        "net/mptcp/protocol.c:__mptcp_update_rmem",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_move_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222016,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589115883,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2747",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clear_xmit",
        "net/mptcp/protocol.c:__mptcp_update_rmem",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589115792,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589834363,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2878",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:mptcp_destroy_common",
        "net/mptcp/protocol.c:__mptcp_update_rmem",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:mptcp_alloc_tx_skb",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:__mptcp_clean_una"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589834272,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591357907,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:3041",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sock_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp.c:tcp_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_try_rmem_schedule",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:dfrag_clear",
        "net/mptcp/protocol.c:__mptcp_mem_reclaim_partial"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591357776,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593125184,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:3121",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:dfrag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593125024,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593577808,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:3182",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:dfrag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593577648,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594350304,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:3192",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_setsockopt",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_recvmsg",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_remove_empty_skb",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse",
        "net/ipv4/tcp_output.c:tcp_trim_head",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/protocol.c:dfrag_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594350128,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501869956,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501869640,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234638172,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234637804,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295279924,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:__skb_free_datagram_locked",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:sk_stream_alloc_skb",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295279616,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278197136,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278196830,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587971115,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970912,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587684219,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587684016,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588302891,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302688,
      "name": "__sk_mem_reclaim",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __sk_mem_reclaim(struct sock * sk, int amount)
```

```json
{
  "name": "__sk_mem_reclaim",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588438267,
      "name": "__sk_mem_reclaim",
      "external": true,
      "loc": "net/core/sock.c:2624",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock.c:sock_rfree",
        "net/core/sock.c:sk_clear_memalloc"
      ],
      "caller_func": [
        "net/core/datagram.c:skb_kill_datagram",
        "net/core/datagram.c:skb_free_datagram",
        "net/core/stream.c:sk_stream_kill_queues",
        "net/core/filter.c:bpf_msg_pop_data",
        "net/core/skmsg.c:sk_msg_trim",
        "net/core/skmsg.c:__sk_msg_free_partial",
        "net/core/skmsg.c:sk_msg_free_elem",
        "net/core/skmsg.c:sk_msg_return",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/core/skmsg.c:sk_msg_return_zero",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_write_queue_purge",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_event_data_recv",
        "net/ipv4/tcp_output.c:tcp_send_synack",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/af_inet.c:inet_sock_destruct",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588438064,
      "name": "__sk_mem_reclaim",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
