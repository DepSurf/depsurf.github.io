# Function: <code>inet_csk_reset_keepalive_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586595264,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:403",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_set_keepalive",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586595264,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587038976,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:398",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_set_keepalive",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587038976,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587235152,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:402",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_set_keepalive",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235152,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587365168,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:528",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365168,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587885296,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:528",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587885296,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231984,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:523",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231984,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588419152,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:539",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588419152,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588823056,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:535",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823056,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589046208,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589046208,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590007584,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:581",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590007584,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590050080,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:581",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590050080,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589964848,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:581",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589964848,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590731936,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:590",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590731936,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592361616,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:594",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_keepidle_locked",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592361616,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594207808,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:755",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_keepidle_locked",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207808,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594594832,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:779",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_keepidle_locked",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594594832,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595398496,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:780",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sock_set_keepidle_locked",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595398496,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502658360,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502658360,
      "name": "inet_csk_reset_keepalive_timer",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235361168,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235361168,
      "name": "inet_csk_reset_keepalive_timer",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296261072,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296261072,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278797528,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278797528,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588652592,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588652592,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588364576,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588364576,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589088768,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589088768,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void inet_csk_reset_keepalive_timer(struct sock * sk, long unsigned int len)
```

```json
{
  "name": "inet_csk_reset_keepalive_timer",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589128368,
      "name": "inet_csk_reset_keepalive_timer",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:555",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_minisocks.c:tcp_create_openreq_child"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589128368,
      "name": "inet_csk_reset_keepalive_timer",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
