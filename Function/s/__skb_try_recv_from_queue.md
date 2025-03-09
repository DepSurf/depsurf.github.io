# Function: <code>__skb_try_recv_from_queue</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586972944,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:164",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586972944,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471168,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471168,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776112,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:163",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776112,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587907824,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:163",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587907824,
      "name": "__skb_try_recv_from_queue",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216960,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216960,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588421728,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421728,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589288592,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:167",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589288592,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287248,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:167",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287248,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589181168,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:167",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181168,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589902656,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:167",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589902656,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 430
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591432608,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591432608,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593198816,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593198816,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593658768,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593658768,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594436704,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:166",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594436704,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501938904,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501938904,
      "name": "__skb_try_recv_from_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234696392,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234696392,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295359808,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295359808,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278246240,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278246240,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588028512,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588028512,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587741600,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741600,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588360288,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588360288,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err, struct sk_buff * * last)
```

```json
{
  "name": "__skb_try_recv_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588495840,
      "name": "__skb_try_recv_from_queue",
      "external": true,
      "loc": "net/core/datagram.c:165",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_try_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/ipv4/udp.c:__skb_recv_udp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588495840,
      "name": "__skb_try_recv_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
struct sk_buff * __skb_try_recv_from_queue(struct sock * sk, struct sk_buff_head * queue, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err, struct sk_buff * * last)
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
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int * peeked</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, queue, flags, destructor, peeked, off, err, last</code> ➡️ <code>sk, queue, flags, destructor, off, err, last</code>
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
<b>Param removed. </b>
<code>void (*)(struct sock *, struct sk_buff *) destructor</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, queue, flags, destructor, off, err, last</code> ➡️ <code>sk, queue, flags, off, err, last</code>
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
