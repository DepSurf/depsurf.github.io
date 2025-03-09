# Function: <code>reqsk_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204791,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586597628,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586636290,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586696432,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071586720940,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587328353,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696432,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587328353,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586625639,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587041969,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587087524,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147381,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071587168856,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826548,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147200,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071587826548,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586810167,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587238257,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587283930,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587346373,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071587368071,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588041102,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:120",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587346192,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071588041102,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586934551,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587368683,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_child_forget",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587415603,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587478517,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071587500732,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587989120,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587478368,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446744071587989120,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587427591,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587890108,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587935511,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001205,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588022917,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588525872,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001376,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071588525872,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587731943,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588239126,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284740,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588356365,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588373805,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588892899,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588352048,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588889936,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587866167,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588424278,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588474392,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588546795,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588564173,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588763099,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116362,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:121",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588542768,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071589113440,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588171026,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588828258,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588880386,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588957772,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588975534,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569651,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588953616,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589566656,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588376226,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589051511,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105371,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589182284,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071589199937,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589793812,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589177904,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589790800,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589238818,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590012081,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590068589,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590153398,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590171185,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590815860,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143648,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071590808336,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589238210,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590054657,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590111926,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202454,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590220353,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590466366,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590875976,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590192496,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071590868288,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589132002,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589968813,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590030887,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590116589,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590135357,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590392142,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590805114,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590105712,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071590797376,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589851682,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590736559,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590802615,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590893718,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071590915194,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591187366,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591623429,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:130",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881024,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    },
    {
      "addr": 18446744071591610656,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591376099,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592366637,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592436472,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592532072,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071592555202,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592846702,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593316147,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592521568,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071593303184,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593136707,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594214429,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594290440,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594390163,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071594414642,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594723742,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595221078,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594379424,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071595207792,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593589523,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594601629,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594676633,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594778520,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071594804007,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595115822,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595616968,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594767664,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071595603920,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594362307,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595405245,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595482362,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589520,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071595615207,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595929298,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596464166,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:132",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595575936,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
    },
    {
      "addr": 18446744071596445904,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501888112,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502663908,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502717080,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502799968,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446603336502819804,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503497828,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502784888,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446603336503487288,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234650076,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3235364888,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 3235414808,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3235503524,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 3235521704,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 3236151184,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235496612,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    },
    {
      "addr": 3236145140,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295295096,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296266000,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296341864,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296440864,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 13835058055296467324,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297288888,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296430192,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    },
    {
      "addr": 13835058055297280016,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278205106,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278801756,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278849326,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278917160,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278934076,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279471712,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587983010,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588657895,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588711755,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588788668,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588806321,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589398180,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588784288,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589395168,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587696114,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588369879,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588423739,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500604,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071588518257,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589123172,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496224,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589120160,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588314786,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589094071,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589147931,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589224844,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071589242497,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835044,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220464,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589832032,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_put(struct request_sock * req)
```

```json
{
  "name": "reqsk_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588450018,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589133725,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:inet_csk_listen_stop",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589187778,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589264972,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446744071589283040,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886308,
      "name": "reqsk_put",
      "external": false,
      "loc": "include/net/request_sock.h:123",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260576,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071589883296,
      "name": "reqsk_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void reqsk_put(struct request_sock * req)
```
</details>
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
