# Function: <code>sk_reset_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586191328,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2349",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191328,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586613856,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2422",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586613856,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586797936,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2446",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_ack",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586797936,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586921424,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2606",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_output.c:tcp_schedule_loss_probe",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586921424,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413488,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2665",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413488,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587717088,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2740",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587717088,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587850336,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2684",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587850336,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588154480,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2827",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154480,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588359728,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588359728,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589224848,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2971",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_reset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589224848,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589222944,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2943",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack_probe",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_reset_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589222944,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589116720,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2966",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_reset_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116720,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589835152,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:3097",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589835152,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591358160,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:3282",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591358160,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593112224,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:3362",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_reset_timeout",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593112224,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593564384,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:3395",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_reset_timeout",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593564384,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594336976,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:3405",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_create_child",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost",
        "net/mptcp/protocol.c:mptcp_subflow_process_delegated",
        "net/mptcp/protocol.c:mptcp_subflow_shutdown",
        "net/mptcp/protocol.c:mptcp_reset_tout_timer",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_clean_una",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer",
        "net/mptcp/pm_netlink.c:mptcp_pm_add_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594336976,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501860496,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501860496,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234627160,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234627160,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295273392,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295273392,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278187498,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278187498,
      "name": "sk_reset_timer",
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966512,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966512,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587679616,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587679616,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588298288,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588298288,
      "name": "sk_reset_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void sk_reset_timer(struct sock * sk, struct timer_list * timer, long unsigned int expires)
```

```json
{
  "name": "sk_reset_timer",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588433472,
      "name": "sk_reset_timer",
      "external": true,
      "loc": "net/core/sock.c:2842",
      "file": "net/core/sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_reset_keepalive_timer",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_ack",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_output.c:tcp_send_probe0",
        "net/ipv4/tcp_output.c:tcp_send_delayed_ack",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_output.c:__tcp_push_pending_frames",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_delack_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_v4_err",
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen",
        "net/ipv4/tcp_recovery.c:tcp_rack_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588433472,
      "name": "sk_reset_timer",
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
