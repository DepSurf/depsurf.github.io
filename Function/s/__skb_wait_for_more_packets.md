# Function: <code>__skb_wait_for_more_packets</code>

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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586660592,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:86",
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
      "addr": 18446744071586660592,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845696,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:86",
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
      "addr": 18446744071586845696,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586968832,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:86",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968832,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587466896,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587466896,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587771824,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:85",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587771824,
      "name": "__skb_wait_for_more_packets",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587905536,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:85",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587905536,
      "name": "__skb_wait_for_more_packets",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588213536,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588213536,
      "name": "__skb_wait_for_more_packets",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588418256,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588418256,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589285728,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:88",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285728,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589284224,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:88",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589284224,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178128,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:88",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178128,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589900688,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:88",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589900688,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591430464,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:86",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430464,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593196560,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:86",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593196560,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593655936,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:86",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593655936,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __skb_wait_for_more_packets(struct sock * sk, struct sk_buff_head * queue, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594433888,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:__unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594433888,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501937816,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501937816,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234695776,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234695776,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295358832,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295358832,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278243368,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278243368,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588025040,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025040,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738128,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738128,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588356816,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356816,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```

```json
{
  "name": "__skb_wait_for_more_packets",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588492400,
      "name": "__skb_wait_for_more_packets",
      "external": true,
      "loc": "net/core/datagram.c:87",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/datagram.c:__skb_recv_datagram",
        "net/ipv4/udp.c:__skb_recv_udp",
        "net/unix/af_unix.c:unix_dgram_recvmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588492400,
      "name": "__skb_wait_for_more_packets",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
int __skb_wait_for_more_packets(struct sock * sk, int * err, long int * timeo_p, const struct sk_buff * skb)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sk_buff_head * queue</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, err, timeo_p, skb</code> ➡️ <code>sk, queue, err, timeo_p, skb</code>
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
