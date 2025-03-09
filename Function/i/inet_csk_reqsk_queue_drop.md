# Function: <code>inet_csk_reqsk_queue_drop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586599328,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:540",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599328,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 537
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043104,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:531",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043104,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587239376,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:535",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239376,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587370224,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:661",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587370224,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587891376,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:660",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891376,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588236688,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:655",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588236688,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588425664,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:674",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425664,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588829536,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:669",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588829536,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589051904,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589051904,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590014136,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:709",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012832,
      "name": "inet_csk_reqsk_queue_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071590013408,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590056785,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:708",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler"
      ],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055408,
      "name": "inet_csk_reqsk_queue_drop.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    },
    {
      "addr": 18446744071590055984,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589970512,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:708",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589970512,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590738704,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:777",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590738704,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 646
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
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592368912,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:781",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592368912,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 627
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
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594216736,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:943",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594216736,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 652
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
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594603936,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:967",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594603936,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
bool inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595407616,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:968",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595407616,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 670
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502661792,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502661792,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235365488,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235365488,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 620
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296266800,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296266800,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278802306,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278802306,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588658288,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658288,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588370272,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588370272,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589094464,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589094464,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
void inet_csk_reqsk_queue_drop(struct sock * sk, struct request_sock * req)
```

```json
{
  "name": "inet_csk_reqsk_queue_drop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589134176,
      "name": "inet_csk_reqsk_queue_drop",
      "external": true,
      "loc": "net/ipv4/inet_connection_sock.c:689",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/inet_connection_sock.c:reqsk_timer_handler",
        "net/ipv4/tcp.c:tcp_abort",
        "net/ipv4/tcp_ipv4.c:tcp_req_err",
        "net/ipv4/tcp_minisocks.c:tcp_check_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589134176,
      "name": "inet_csk_reqsk_queue_drop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
