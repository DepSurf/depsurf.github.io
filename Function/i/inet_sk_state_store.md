# Function: <code>inet_sk_state_store</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588459824,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1285",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588459824,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588653504,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1285",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588653504,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066160,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066160,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589290480,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589290480,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590266608,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1323",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_shutdown",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_accept",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_socket_create",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590266608,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590319696,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1321",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_check_fastclose",
        "net/mptcp/subflow.c:subflow_state_change",
        "net/mptcp/subflow.c:__mptcp_error_report",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_finish_connect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590319696,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590235712,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1325",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_set_connected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590235712,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591019056,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1327",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_set_connected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591019056,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592665472,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1322",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_stream_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:mptcp_close",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_set_connected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592665472,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594533072,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1342",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:__mptcp_check_send_data_fin",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:subflow_syn_recv_sock",
        "net/mptcp/subflow.c:mptcp_set_connected"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594533072,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594924848,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1341",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone_init",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_unaccepted_force_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/subflow.c:__mptcp_error_report",
        "net/mptcp/subflow.c:mptcp_set_connected",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594924848,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595737104,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1361",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state",
        "net/mptcp/protocol.c:mptcp_stream_accept",
        "net/mptcp/protocol.c:mptcp_listen",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_connect",
        "net/mptcp/protocol.c:mptcp_sk_clone_init",
        "net/mptcp/protocol.c:mptcp_disconnect",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_close",
        "net/mptcp/protocol.c:__mptcp_unaccepted_force_close",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_close_ssk",
        "net/mptcp/protocol.c:__mptcp_error_report",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_create_listen_socket"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737104,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502921944,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502921944,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235614864,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235614864,
      "name": "inet_sk_state_store",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296592704,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296592704,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279013868,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279013868,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588896656,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588896656,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588608592,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608592,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589333040,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589333040,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
void inet_sk_state_store(struct sock * sk, int newstate)
```

```json
{
  "name": "inet_sk_state_store",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589375216,
      "name": "inet_sk_state_store",
      "external": true,
      "loc": "net/ipv4/af_inet.c:1291",
      "file": "net/ipv4/af_inet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_start",
        "net/ipv4/tcp.c:tcp_set_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375216,
      "name": "inet_sk_state_store",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void inet_sk_state_store(struct sock * sk, int newstate)
```
</details>
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
