# Function: <code>sk_stream_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586242768,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:180",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586242768,
      "name": "sk_stream_error",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586666480,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:180",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666480,
      "name": "sk_stream_error",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586851440,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:179",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851440,
      "name": "sk_stream_error",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974464,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:180",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974464,
      "name": "sk_stream_error",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587472672,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:181",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587472672,
      "name": "sk_stream_error",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587777632,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:181",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_sendmsg",
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777632,
      "name": "sk_stream_error",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910528,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:181",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910528,
      "name": "sk_stream_error",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588218560,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588218560,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588423184,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588423184,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589289648,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289648,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589288368,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589288368,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589182288,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589182288,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589904000,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589904000,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591433728,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591433728,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593200000,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:184",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593200000,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593659968,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:184",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593659968,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594437904,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:186",
      "file": "net/core/stream.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg",
        "net/mptcp/protocol.c:mptcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594437904,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501941000,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501941000,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234697848,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234697848,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295361360,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295361360,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278247414,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278247414,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588029968,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029968,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587743056,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587743056,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588361744,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361744,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int sk_stream_error(struct sock * sk, int flags, int err)
```

```json
{
  "name": "sk_stream_error",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588497296,
      "name": "sk_stream_error",
      "external": true,
      "loc": "net/core/stream.c:183",
      "file": "net/core/stream.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg_locked",
        "net/ipv4/tcp.c:do_tcp_sendpages",
        "net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588497296,
      "name": "sk_stream_error",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
