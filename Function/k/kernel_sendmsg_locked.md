# Function: <code>kernel_sendmsg_locked</code>

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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587389504,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:660",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389504,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587690784,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:664",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690784,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824896,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:644",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824896,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588127616,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588127616,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588332752,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588332752,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589193152,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:709",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193152,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191680,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:709",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191680,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589085200,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:711",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:__skb_send_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589085200,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589802672,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:761",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:__skb_send_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589802672,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591320752,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:771",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:__skb_send_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320752,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593074336,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:773",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:__skb_send_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593074336,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593525840,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:788",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593525840,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594297264,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:809",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594297264,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501826488,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501826488,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234608844,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234608844,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295228096,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295228096,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278173052,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278173052,
      "name": "kernel_sendmsg_locked",
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587939536,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587939536,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587652640,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587652640,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588271312,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588271312,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
```

```json
{
  "name": "kernel_sendmsg_locked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588406592,
      "name": "kernel_sendmsg_locked",
      "external": true,
      "loc": "net/socket.c:694",
      "file": "net/socket.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock.c:sock_no_sendpage_locked",
        "net/core/skbuff.c:skb_send_sock_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406592,
      "name": "kernel_sendmsg_locked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int kernel_sendmsg_locked(struct sock * sk, struct msghdr * msg, struct kvec * vec, size_t num, size_t size)
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
