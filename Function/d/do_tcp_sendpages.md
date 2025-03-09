# Function: <code>do_tcp_sendpages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586615484,
      "name": "do_tcp_sendpages",
      "external": false,
      "loc": "net/ipv4/tcp.c:889",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587060295,
      "name": "do_tcp_sendpages",
      "external": false,
      "loc": "net/ipv4/tcp.c:878",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587256911,
      "name": "do_tcp_sendpages",
      "external": false,
      "loc": "net/ipv4/tcp.c:882",
      "file": "net/ipv4/tcp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587388992,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:904",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388992,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1409
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587905280,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:933",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905280,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1435
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588256848,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:938",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/sockmap.c:bpf_tcp_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588256848,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1484
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588445056,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:937",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588445056,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1473
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588850368,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:954",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588850368,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1527
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589073664,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589073664,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590038240,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:963",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590038240,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1620
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590073680,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:1029",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590073680,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 802
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589988160,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:1028",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589988160,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:1025",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592715448,
      "name": "do_tcp_sendpages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071590757728,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:1037",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594601687,
      "name": "do_tcp_sendpages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071592387136,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:1039",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_sendpage",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push",
        "net/xfrm/espintcp.c:espintcp_sendskmsg_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596337227,
      "name": "do_tcp_sendpages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071594237632,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 819
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502690136,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502690136,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1540
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235391424,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235391424,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1592
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296299472,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296299472,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2052
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278820576,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278820576,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588680048,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588680048,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392032,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392032,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589116224,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589116224,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "do_tcp_sendpages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589156048,
      "name": "do_tcp_sendpages",
      "external": true,
      "loc": "net/ipv4/tcp.c:956",
      "file": "net/ipv4/tcp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589156048,
      "name": "do_tcp_sendpages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1586
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
ssize_t do_tcp_sendpages(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```
</details>
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
