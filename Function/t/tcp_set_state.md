# Function: <code>tcp_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586604384,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:1910",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586604384,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587048064,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:1919",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587048064,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587243536,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:1957",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587243536,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587374928,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2001",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374928,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587895232,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2039",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587895232,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588242224,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2186",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588242224,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429536,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2197",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429536,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588834720,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2208",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588834720,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589057840,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057840,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590020736,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2279",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590020736,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590063088,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2527",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_check_fastclose",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063088,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589977664,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2570",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589977664,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2570",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592715264,
      "name": "tcp_set_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071590750736,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2597",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594601501,
      "name": "tcp_set_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071592382944,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 510
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594229920,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2697",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/subflow.c:subflow_check_data_avail",
        "net/mptcp/subflow.c:mptcp_subflow_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594229920,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594617120,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2583",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594617120,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595420064,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2594",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:__tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_fastopen",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:subflow_check_data_avail"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595420064,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 343
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502679600,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502679600,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235373644,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235373644,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296277600,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296277600,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278807680,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_done",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278807680,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588664224,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588664224,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376208,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376208,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589100400,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589100400,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
void tcp_set_state(struct sock * sk, int state)
```

```json
{
  "name": "tcp_set_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140160,
      "name": "tcp_set_state",
      "external": true,
      "loc": "net/ipv4/tcp.c:2207",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_close",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv4/tcp_ipv4.c:tcp_v4_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect",
        "net/ipv6/tcp_ipv6.c:tcp_v6_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140160,
      "name": "tcp_set_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 458
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
