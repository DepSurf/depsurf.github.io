# Function: <code>__zerocopy_sg_from_iter</code>

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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587467920,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:583",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587467920,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587772864,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:581",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587772864,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 543
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587906400,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:616",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587906400,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588215216,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588215216,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 519
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588420048,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588420048,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589286576,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:619",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589286576,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 609
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589285088,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:619",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285088,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 768
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178992,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:619",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178992,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 761
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589901552,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:619",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589901552,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1021
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591430880,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:616",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/ipv4/ip_output.c:__ip_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430880,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1281
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
int __zerocopy_sg_from_iter(struct msghdr * msg, struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593197296,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:613",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sg_from_iter",
        "io_uring/net.c:io_sg_from_iter_iovec",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/ipv4/ip_output.c:__ip_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593197296,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1166
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
int __zerocopy_sg_from_iter(struct msghdr * msg, struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:613",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sg_from_iter",
        "io_uring/net.c:io_sg_from_iter_iovec",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/ipv4/ip_output.c:__ip_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596852155,
      "name": "__zerocopy_sg_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071593656656,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1746
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
int __zerocopy_sg_from_iter(struct msghdr * msg, struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:632",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "io_uring/net.c:io_sg_from_iter",
        "io_uring/net.c:io_sg_from_iter_iovec",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/datagram.c:zerocopy_sg_from_iter",
        "net/ipv4/ip_output.c:__ip_append_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597777114,
      "name": "__zerocopy_sg_from_iter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071594434608,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1743
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501936208,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501936208,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 492
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234694352,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234694352,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295357408,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295357408,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278244872,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278244872,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026832,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026832,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587739920,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587739920,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588358608,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588358608,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
```

```json
{
  "name": "__zerocopy_sg_from_iter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588494160,
      "name": "__zerocopy_sg_from_iter",
      "external": true,
      "loc": "net/core/datagram.c:615",
      "file": "net/core/datagram.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_zerocopy_iter_stream",
        "net/core/skbuff.c:skb_zerocopy_iter_dgram",
        "net/core/datagram.c:zerocopy_sg_from_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588494160,
      "name": "__zerocopy_sg_from_iter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
int __zerocopy_sg_from_iter(struct sock * sk, struct sk_buff * skb, struct iov_iter * from, size_t length)
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct msghdr * msg</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, skb, from, length</code> ➡️ <code>msg, sk, skb, from, length</code>
</li>
</ul>
</details>
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
