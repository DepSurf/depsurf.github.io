# Function: <code>tcp_push</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602048,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:660",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602048,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587045568,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:649",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587045568,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587241616,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:648",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587241616,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587372976,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:670",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587372976,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 281
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587893296,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:699",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587893296,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588240272,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:704",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588240272,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427760,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:704",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427760,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588831760,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:693",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588831760,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589054880,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589054880,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590037088,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:702",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590037088,
      "name": "tcp_push",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068144,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:706",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:mptcp_worker",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:mptcp_push_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068144,
      "name": "tcp_push",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589982496,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:705",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589982496,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590751952,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:702",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590751952,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592384688,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592384688,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594235392,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:699",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594235392,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594622224,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:703",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_eof",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594622224,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595425232,
      "name": "tcp_push",
      "external": true,
      "loc": "net/ipv4/tcp.c:705",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_eof",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/mptcp/protocol.c:__mptcp_retrans",
        "net/mptcp/protocol.c:__mptcp_subflow_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending",
        "net/mptcp/protocol.c:__mptcp_push_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595425232,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 394
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502679248,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502679248,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235370728,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235370728,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296273488,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296273488,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278804888,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278804888,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588661264,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588661264,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588373248,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373248,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589097440,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589097440,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void tcp_push(struct sock * sk, int flags, int mss_now, int nonagle, int size_goal)
```

```json
{
  "name": "tcp_push",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589137200,
      "name": "tcp_push",
      "external": false,
      "loc": "net/ipv4/tcp.c:695",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137200,
      "name": "tcp_push",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
