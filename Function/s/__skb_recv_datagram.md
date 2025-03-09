# Function: <code>__skb_recv_datagram</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586236880,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:194",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_do_read",
        "net/core/datagram.c:skb_recv_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/unix/af_unix.c:unix_dgram_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586236880,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1469
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586661632,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:264",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586661632,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846720,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:270",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/ipv4/udp.c:udp_recvmsg",
        "net/ipv6/udp.c:udpv6_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846720,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586973744,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:293",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586973744,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587471952,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:294",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587471952,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587776912,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:292",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587776912,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * peeked, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587908608,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:292",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587908608,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588217696,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588217696,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588422464,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588422464,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589289360,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:287",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589289360,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589288080,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:287",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589288080,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589182000,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:287",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589182000,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589903488,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:287",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589903488,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591433424,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:285",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591433424,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593199664,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:285",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593199664,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593659632,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:285",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593659632,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, struct sk_buff_head * sk_queue, unsigned int flags, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594437568,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:286",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram",
        "net/xfrm/espintcp.c:espintcp_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594437568,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501939832,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501939832,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234697208,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234697208,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295360960,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295360960,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278246840,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278246840,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588029248,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588029248,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587742336,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587742336,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588361024,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361024,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
struct sk_buff * __skb_recv_datagram(struct sock * sk, unsigned int flags, void (*)(struct sock *, struct sk_buff *) destructor, int * off, int * err)
```

```json
{
  "name": "__skb_recv_datagram",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588496576,
      "name": "__skb_recv_datagram",
      "external": true,
      "loc": "net/core/datagram.c:291",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:skb_recv_datagram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496576,
      "name": "__skb_recv_datagram",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*)(struct sock *, struct sk_buff *) destructor</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, peeked, off, err</code> ➡️ <code>sk, flags, destructor, peeked, off, err</code>
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
<code>sk, flags, destructor, peeked, off, err</code> ➡️ <code>sk, flags, destructor, off, err</code>
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
<code>struct sk_buff_head * sk_queue</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*)(struct sock *, struct sk_buff *) destructor</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, flags, destructor, off, err</code> ➡️ <code>sk, sk_queue, flags, off, err</code>
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
