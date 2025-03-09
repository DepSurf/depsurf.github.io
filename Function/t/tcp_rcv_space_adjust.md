# Function: <code>tcp_rcv_space_adjust</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586643408,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:556",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp_input.c:tcp_data_queue",
        "net/ipv4/tcp_input.c:tcp_rcv_established"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643408,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587089008,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:558",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587089008,
      "name": "tcp_rcv_space_adjust",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587285872,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:581",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587285872,
      "name": "tcp_rcv_space_adjust",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587417536,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:588",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp_input.c:tcp_rcv_established",
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417536,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587937504,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:578",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937504,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588286864,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:610",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588286864,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 497
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588475584,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:595",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588475584,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588882416,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:601",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588882416,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589106480,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589106480,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590073616,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:605",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590073616,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590118944,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:669",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118944,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590032608,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:669",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590032608,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:692",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592717022,
      "name": "tcp_rcv_space_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071590803712,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:701",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594603398,
      "name": "tcp_rcv_space_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071592438192,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:701",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_skb",
        "net/ipv4/tcp.c:tcp_read_skb",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596338714,
      "name": "tcp_rcv_space_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071594292176,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:700",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_eat_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596868114,
      "name": "tcp_rcv_space_adjust.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 170
    },
    {
      "addr": 18446744071594678352,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595483312,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:728",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg_locked",
        "net/ipv4/tcp.c:tcp_zerocopy_receive",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_done",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv4/tcp_bpf.c:tcp_eat_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595483312,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502723120,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502723120,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235426444,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235426444,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296343280,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296343280,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278850408,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278850408,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588712864,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588712864,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588424848,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588424848,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589149040,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149040,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
void tcp_rcv_space_adjust(struct sock * sk)
```

```json
{
  "name": "tcp_rcv_space_adjust",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589188912,
      "name": "tcp_rcv_space_adjust",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:603",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/ipv4/tcp.c:tcp_read_sock",
        "net/ipv4/tcp.c:tcp_read_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589188912,
      "name": "tcp_rcv_space_adjust",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
