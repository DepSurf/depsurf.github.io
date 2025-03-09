# Function: <code>tcp_write_queue_purge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586611377,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1449",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586695443,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1449",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587055980,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1462",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587144224,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1462",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587251891,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1533",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587334736,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1533",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587383602,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1584",
      "file": "net/ipv4/tcp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_disconnect"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587467802,
      "name": "tcp_write_queue_purge",
      "external": false,
      "loc": "include/net/tcp.h:1584",
      "file": "net/ipv4/tcp_ipv4.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915120,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2351",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915120,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 482
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588263440,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2520",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263440,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451680,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2522",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451680,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588856976,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2533",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588856976,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 898
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589080544,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589080544,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590044656,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2608",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590044656,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1107
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590086288,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2861",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590086288,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1022
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590001040,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2915",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590001040,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590771520,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2940",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590771520,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 938
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592404480,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2968",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592404480,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594252368,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:3065",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594252368,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594639072,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2951",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594639072,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595442400,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2963",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_input.c:tcp_reset",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_keepalive_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595442400,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 804
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502696936,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502696936,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235398276,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235398276,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296308320,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296308320,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1116
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278826504,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278826504,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 738
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588686928,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588686928,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588398912,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588398912,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589123104,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589123104,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
void tcp_write_queue_purge(struct sock * sk)
```

```json
{
  "name": "tcp_write_queue_purge",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589162928,
      "name": "tcp_write_queue_purge",
      "external": true,
      "loc": "net/ipv4/tcp.c:2536",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_disconnect",
        "net/ipv4/tcp_output.c:tcp_connect_init",
        "net/ipv4/tcp_timer.c:tcp_write_err",
        "net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589162928,
      "name": "tcp_write_queue_purge",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 929
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void tcp_write_queue_purge(struct sock * sk)
```
</details>
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
