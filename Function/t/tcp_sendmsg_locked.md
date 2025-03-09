# Function: <code>tcp_sendmsg_locked</code>

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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587906944,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1182",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587906944,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3688
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588258544,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1175",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588258544,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3412
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588446752,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1174",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588446752,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1177",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860834,
      "name": "tcp_sendmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588852096,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3338
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589075456,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589075456,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3542
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590040112,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1185",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590040112,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2912
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590069760,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1204",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590069760,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2942
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589984096,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1203",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589984096,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3085
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1200",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592715423,
      "name": "tcp_sendmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590753552,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3186
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1213",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594601713,
      "name": "tcp_sendmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071592388240,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3171
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1214",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596337253,
      "name": "tcp_sendmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    },
    {
      "addr": 18446744071594239376,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2736
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1032",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596866805,
      "name": "tcp_sendmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071594624544,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3405
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1038",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597791713,
      "name": "tcp_sendmsg_locked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    },
    {
      "addr": 18446744071595427584,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3434
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502691952,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502691952,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3160
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235393232,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235393232,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3404
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296301872,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296301872,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4092
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278822036,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278822036,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2822
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588681840,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588681840,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3542
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393824,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393824,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3542
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589118016,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589118016,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3542
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
```

```json
{
  "name": "tcp_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589157840,
      "name": "tcp_sendmsg_locked",
      "external": true,
      "loc": "net/ipv4/tcp.c:1178",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157840,
      "name": "tcp_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3542
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
int tcp_sendmsg_locked(struct sock * sk, struct msghdr * msg, size_t size)
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
