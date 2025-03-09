# Function: <code>reqsk_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_free(struct request_sock * req)
```

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204809,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588594,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586597648,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
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
      "addr": 18446744071586635897,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586696447,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721240,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586885904,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ]
    },
    {
      "addr": 18446744071587328368,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587231676,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586885904,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void reqsk_free(struct request_sock * req)
```

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586625648,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587030463,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587041969,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
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
      "addr": 18446744071587086945,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587147393,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587168869,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587335641,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ]
    },
    {
      "addr": 18446744071587826562,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587688747,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587335168,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void reqsk_free(struct request_sock * req)
```

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586810176,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226575,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587238257,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
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
      "addr": 18446744071587283915,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587346385,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587368084,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587538489,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ]
    },
    {
      "addr": 18446744071588041116,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587897494,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:108",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587538016,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void reqsk_free(struct request_sock * req)
```

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586934560,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587358631,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587368683,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
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
      "addr": 18446744071587415617,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587478577,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587500745,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587684303,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ]
    },
    {
      "addr": 18446744071587989136,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588054817,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683872,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void reqsk_free(struct request_sock * req)
```

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587427606,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587879291,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587890127,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
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
      "addr": 18446744071587935531,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588001271,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588022936,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588211017,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ]
    },
    {
      "addr": 18446744071588525895,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:reqsk_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588592870,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588210544,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587731958,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588222932,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588239454,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
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
      "addr": 18446744071588284760,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588356565,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373824,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588567477,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588893099,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588958018,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587866182,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588410164,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588424606,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
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
      "addr": 18446744071588473312,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588546994,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564192,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588764975,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589116561,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589181991,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:109",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588171043,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588813943,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588828279,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071588880406,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588957990,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588975553,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589197985,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589569861,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589635785,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588376243,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589037255,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589051532,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071589105391,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589182502,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589199956,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589423361,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589794022,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589859997,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589238869,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589998749,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590012504,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071590069594,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590153685,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590171276,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590410532,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590816138,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590887226,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589238261,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590041037,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590055080,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
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
      "addr": 18446744071590113002,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590202741,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590220444,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_fastopen_queue_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590468842,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590876248,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590948715,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589132053,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589955229,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589969236,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
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
      "addr": 18446744071590032158,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590116892,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590135531,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590394609,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590805409,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590878670,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589851733,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590722429,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590736983,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
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
      "addr": 18446744071590802084,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590894060,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590915573,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591189918,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591623752,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591709318,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:124",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591376147,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592351348,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592367071,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
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
      "addr": 18446744071592437697,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592532421,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592555525,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592849458,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593316435,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593409159,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593136755,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594190836,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594214863,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
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
      "addr": 18446744071594291665,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594390404,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594414965,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594726562,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595221310,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595319559,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593589571,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594577940,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594602063,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
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
      "addr": 18446744071594677852,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594778761,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594804314,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595118642,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595617198,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595714591,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594362355,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595381620,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595405679,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
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
      "addr": 18446744071595481564,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595589760,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595615514,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595931469,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_tcp_reqsk_alloc",
        "net/ipv4/syncookies.c:tcp_get_cookie_sock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596464413,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596562507,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:126",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501888128,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502647196,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502664056,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446603336502717096,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502800200,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502819828,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503076124,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503498048,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503577096,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234650092,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 3235351232,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235365208,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 3235414824,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3235503732,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 3235521720,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 3235759120,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check",
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 3236151388,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 3236224252,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295295136,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296247680,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296266496,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 13835058055296341260,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296441228,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296467364,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296780860,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297289208,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297380816,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
void reqsk_free(struct request_sock * req)
```

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278205124,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278787930,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278802110,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446743936278849344,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278912628,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv"
      ]
    },
    {
      "addr": 18446743936278934094,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279132320,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279460722,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    },
    {
      "addr": 18446743936279533436,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278900050,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446743936279460722,
      "name": "reqsk_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587983027,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588643639,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588657916,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071588711775,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588788886,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588806340,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589027729,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589398390,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589464365,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587696131,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588355623,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588369900,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071588423759,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588500822,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588518276,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588752769,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589123382,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589189357,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588314803,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079815,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589094092,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071589147951,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589225062,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589242516,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589464113,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589835254,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589901229,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reqsk_free",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588450035,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/core/request_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/request_sock.c:reqsk_fastopen_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589119239,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/inet_hashtables.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589133800,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
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
      "addr": 18446744071589187798,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_conn_request",
        "net/ipv4/tcp_input.c:tcp_conn_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589265190,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_rcv",
        "net/ipv4/tcp_ipv4.c:tcp_req_err"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589283072,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/tcp_fastopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_fastopen.c:tcp_try_fastopen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589510449,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv4/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/syncookies.c:cookie_v4_check"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589886518,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589953473,
      "name": "reqsk_free",
      "external": false,
      "loc": "include/net/request_sock.h:117",
      "file": "net/ipv6/syncookies.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/syncookies.c:cookie_v6_check"
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void reqsk_free(struct request_sock * req)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void reqsk_free(struct request_sock * req)
```
</details>
</li>
</ul>
