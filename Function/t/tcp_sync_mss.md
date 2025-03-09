# Function: <code>tcp_sync_mss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664672,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1386",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664672,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587110928,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1401",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv4/tcp_ipv4.c:tcp_v4_mtu_reduced",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587110928,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309136,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1424",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309136,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587440624,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1503",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587440624,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587961856,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1557",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961856,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588311696,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1548",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588311696,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588500784,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1536",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588500784,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588909824,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1549",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588909824,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589133536,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589133536,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590104064,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1631",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590104064,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590151008,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1798",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590151008,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590064608,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1799",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590064608,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590838288,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1799",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590838288,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 319
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592473984,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1795",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592473984,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594329616,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1792",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594329616,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594717056,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1784",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594717056,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595521120,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1827",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_send_syn_data",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595521120,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502747224,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502747224,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235453488,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235453488,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296376384,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296376384,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278873842,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278873842,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588739920,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588739920,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451872,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451872,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589176096,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176096,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
unsigned int tcp_sync_mss(struct sock * sk, u32 pmtu)
```

```json
{
  "name": "tcp_sync_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589216160,
      "name": "tcp_sync_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_output.c:tcp_current_mss",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589216160,
      "name": "tcp_sync_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
