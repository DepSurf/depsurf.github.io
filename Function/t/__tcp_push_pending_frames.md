# Function: <code>__tcp_push_pending_frames</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586674768,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2288",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_fastretrans_alert",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674768,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587121264,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2306",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587121264,
      "name": "__tcp_push_pending_frames",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587318976,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2426",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587318976,
      "name": "__tcp_push_pending_frames",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587450464,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2503",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450464,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587971792,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2556",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587971792,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588321488,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2537",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588321488,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588510576,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2568",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588510576,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924656,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2595",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924656,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589148592,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148592,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590117136,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2687",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590117136,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164848,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2859",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164848,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590079456,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2864",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590079456,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590854096,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2864",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590854096,
      "name": "__tcp_push_pending_frames",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592490240,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2865",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592490240,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594345504,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2867",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594345504,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594733376,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2909",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_setsockopt",
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594733376,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595538736,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2967",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_nodelay",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/mptcp/protocol.c:mptcp_sendmsg_frag"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595538736,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502764208,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502764208,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235468792,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235468792,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296395120,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296395120,
      "name": "__tcp_push_pending_frames",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278886720,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278886720,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588754976,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754976,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588466928,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466928,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191152,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191152,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void __tcp_push_pending_frames(struct sock * sk, unsigned int cur_mss, int nonagle)
```

```json
{
  "name": "__tcp_push_pending_frames",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231216,
      "name": "__tcp_push_pending_frames",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2622",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:tcp_push",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_output.c:tcp_send_fin"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231216,
      "name": "__tcp_push_pending_frames",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
