# Function: <code>tcp_recv_timestamp</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910784,
      "name": "tcp_recv_timestamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:1734",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910784,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 375
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
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588246496,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588436565,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1864",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp.c:tcp_recvmsg"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588832944,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1854",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832944,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589056032,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589056032,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590021216,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1921",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590021216,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590063584,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:2160",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063584,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589978160,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:2203",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978160,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590765792,
      "name": "tcp_recv_timestamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:2203",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590765792,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592398480,
      "name": "tcp_recv_timestamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:2230",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592398480,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 491
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594249632,
      "name": "tcp_recv_timestamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:2330",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594249632,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 507
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594636320,
      "name": "tcp_recv_timestamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:2216",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594636320,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595439632,
      "name": "tcp_recv_timestamp",
      "external": true,
      "loc": "net/ipv4/tcp.c:2223",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:do_tcp_getsockopt",
        "net/ipv4/tcp.c:tcp_recvmsg",
        "net/mptcp/protocol.c:mptcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595439632,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 523
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502669512,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502669512,
      "name": "tcp_recv_timestamp",
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235372160,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235372160,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296275472,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296275472,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278806080,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278806080,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588662416,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588662416,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588374400,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588374400,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589098592,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098592,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```

```json
{
  "name": "tcp_recv_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589138352,
      "name": "tcp_recv_timestamp",
      "external": false,
      "loc": "net/ipv4/tcp.c:1855",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589138352,
      "name": "tcp_recv_timestamp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 461
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
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping * tss)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping * tss)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void tcp_recv_timestamp(struct msghdr * msg, const struct sock * sk, struct scm_timestamping_internal * tss)
```
</details>
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
