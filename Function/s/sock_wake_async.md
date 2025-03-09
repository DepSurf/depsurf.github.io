# Function: <code>sock_wake_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586173040,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1062",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173040,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593760,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1059",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593760,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586778128,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1102",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_finish_connect",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586778128,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586899248,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1151",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586899248,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390976,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1170",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390976,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587691824,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1192",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587691824,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587825920,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1179",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587825920,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588128768,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588128768,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588333904,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333904,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589193408,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1316",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193408,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191936,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1294",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191936,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589085456,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1285",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589085456,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589802928,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1355",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589802928,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591321216,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1403",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/sock.c:sock_wfree",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591321216,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593074848,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1408",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/sock.c:sock_wfree",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074848,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593526352,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1437",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/sock.c:sock_wfree",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593526352,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594297776,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1459",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/sock.c:sock_wfree",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594297776,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501830400,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501830400,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234609156,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234609156,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295229520,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295229520,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278173992,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278173992,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587940688,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587940688,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653792,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653792,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588272464,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272464,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int sock_wake_async(struct socket_wq * wq, int how, int band)
```

```json
{
  "name": "sock_wake_async",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588407760,
      "name": "sock_wake_async",
      "external": true,
      "loc": "net/socket.c:1306",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_def_write_space",
        "net/core/sock.c:sock_def_readable",
        "net/core/sock.c:sock_def_error_report",
        "net/core/stream.c:sk_stream_write_space",
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/ipv4/tcp_input.c:tcp_fin",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_shutdown",
        "net/unix/af_unix.c:unix_release_sock",
        "net/unix/af_unix.c:unix_write_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588407760,
      "name": "sock_wake_async",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
