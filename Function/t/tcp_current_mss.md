# Function: <code>tcp_current_mss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666736,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1411",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_may_send_now",
        "net/ipv4/tcp_output.c:tcp_may_send_now",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_write_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666736,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587113040,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1426",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_may_send_now",
        "net/ipv4/tcp_output.c:tcp_may_send_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587113040,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587311072,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1449",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_may_send_now",
        "net/ipv4/tcp_output.c:tcp_may_send_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587311072,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587442704,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1528",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_may_send_now",
        "net/ipv4/tcp_output.c:tcp_may_send_now"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442704,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587964048,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1582",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587964048,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588313488,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1573",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313488,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588502560,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1561",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588502560,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588913072,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1574",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588913072,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589136832,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136832,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590108064,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1656",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108064,
      "name": "tcp_current_mss",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155392,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1823",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155392,
      "name": "tcp_current_mss",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069008,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1824",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069008,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590842832,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1824",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590842832,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592478336,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1820",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592478336,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594334096,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1817",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594334096,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594720656,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1809",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594720656,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595525376,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1852",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595525376,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502752768,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502752768,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235457028,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235457028,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296380512,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296380512,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278876614,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278876614,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588743216,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743216,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588455168,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588455168,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589179392,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179392,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
unsigned int tcp_current_mss(struct sock * sk)
```

```json
{
  "name": "tcp_current_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589219456,
      "name": "tcp_current_mss",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1593",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_send_mss",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_input.c:tcp_sacktag_write_queue",
        "net/ipv4/tcp_output.c:tcp_write_wakeup",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe",
        "net/ipv4/tcp_output.c:tcp_mtu_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219456,
      "name": "tcp_current_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
