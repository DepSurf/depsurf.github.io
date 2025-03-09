# Function: <code>kernel_sendpage_locked</code>

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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587394160,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3381",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587394160,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587694096,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3345",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587694096,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587828192,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3411",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587828192,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588130512,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3700",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588130512,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588335648,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588335648,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589195104,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3660",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589195104,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589193200,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3654",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193200,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589086720,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3640",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_send_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589086720,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589803856,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3525",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_send_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803856,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591322512,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3585",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_send_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322512,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593076336,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3573",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_send_sock",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593076336,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501829344,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501829344,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234611020,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234611020,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295232992,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295232992,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278175770,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278175770,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587942432,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587942432,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587655536,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587655536,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588274208,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588274208,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
```

```json
{
  "name": "kernel_sendpage_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588409520,
      "name": "kernel_sendpage_locked",
      "external": true,
      "loc": "net/socket.c:3781",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_send_sock_locked",
        "net/ipv4/tcp_bpf.c:tcp_bpf_push"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409520,
      "name": "kernel_sendpage_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int kernel_sendpage_locked(struct sock * sk, struct page * page, int offset, size_t size, int flags)
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
