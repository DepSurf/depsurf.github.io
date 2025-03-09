# Function: <code>__skb_try_recv_datagram</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586660960,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:199",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586660960,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846064,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:200",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846064,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 655
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973376,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:245",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973376,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471600,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:246",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471600,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776560,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776560,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587908240,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908240,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588217344,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588217344,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422112,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422112,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589289024,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:242",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289024,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287680,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:242",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287680,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589181600,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:242",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181600,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589903088,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:242",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589903088,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591433008,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:240",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591433008,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593199232,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:240",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593199232,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593659200,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:240",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593659200,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594437136,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:241",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594437136,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501939352,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501939352,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234696792,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234696792,
      "name": "__skb_try_recv_datagram",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295360384,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295360384,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 568
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278246576,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278246576,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028896,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028896,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587741984,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741984,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588360672,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588360672,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588496224,
      "name": "__skb_try_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:244",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496224,
      "name": "__skb_try_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 341
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct sk_buff * __skb_try_recv_datagram(struct sock * sk, unsigned int flags, int * peeked, int * off, int * err, struct sk_buff * * last)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*)(struct sock *, struct sk_buff *) destructor</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, peeked, off, err, last</code> ➡️ <code>sk, flags, destructor, peeked, off, err, last</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int * peeked</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, destructor, peeked, off, err, last</code> ➡️ <code>sk, flags, destructor, off, err, last</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff_head * queue</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*)(struct sock *, struct sk_buff *) destructor</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, destructor, off, err, last</code> ➡️ <code>sk, queue, flags, off, err, last</code>
</li>
</ul>
</details>
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
