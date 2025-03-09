# Function: <code>tcp_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606640,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1574",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606640,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2936
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587050288,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1581",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587050288,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2924
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587246240,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1619",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587246240,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2879
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587380160,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1663",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587380160,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2898
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587911168,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1782",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587911168,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2601
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1919",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266286,
      "name": "tcp_recvmsg.cold.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588244880,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1933",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588454766,
      "name": "tcp_recvmsg.cold.59",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071588434944,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3178
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1944",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588860785,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588843728,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2772
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084433,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589070128,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2015",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048993,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071590031488,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2576
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590078944,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2496",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590078944,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589993376,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2539",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589993376,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590766256,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2539",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590766256,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592398976,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2565",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592398976,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594250160,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2665",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594250160,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594636864,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2551",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594636864,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595440176,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:2562",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg_parser",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595440176,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502676016,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502676016,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2460
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235379796,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235379796,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2816
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296285280,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296285280,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3344
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
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278815398,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278815398,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2242
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588690817,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588676512,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588402801,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071588388496,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126993,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589112688,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2802
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int tcp_recvmsg(struct sock * sk, struct msghdr * msg, size_t len, int nonblock, int flags, int * addr_len)
```

```json
{
  "name": "tcp_recvmsg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_recvmsg",
      "external": true,
      "loc": "net/ipv4/tcp.c:1945",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/af_inet.c:inet_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg",
        "net/ipv6/af_inet6.c:inet6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589166817,
      "name": "tcp_recvmsg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589152512,
      "name": "tcp_recvmsg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2802
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nonblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, len, nonblock, flags, addr_len</code> ➡️ <code>sk, msg, len, flags, addr_len</code>
</li>
</ul>
</details>
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
