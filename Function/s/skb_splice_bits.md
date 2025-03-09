# Function: <code>skb_splice_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags, ssize_t (*)(struct sock *, struct pipe_inode_info *, struct splice_pipe_desc *) splice_cb)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586219920,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:1973",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586219920,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags, ssize_t (*)(struct sock *, struct pipe_inode_info *, struct splice_pipe_desc *) splice_cb)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643584,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:1990",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643584,
      "name": "skb_splice_bits",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828288,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:1969",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828288,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586945920,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:1984",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586945920,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587439872,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2239",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587439872,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587743952,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2255",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587743952,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587878544,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2264",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587878544,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588183792,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2423",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183792,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588389744,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389744,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589248656,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248656,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589248304,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2441",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589248304,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589143360,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2483",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589143360,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589863360,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2555",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589863360,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591390400,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2604",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591390400,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593153776,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2810",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593153776,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593608512,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2974",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593608512,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594383616,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:3062",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594383616,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501900584,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501900584,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234667048,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234667048,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295315888,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295315888,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278219542,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278219542,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587996528,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587996528,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587709632,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709632,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588328304,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588328304,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int skb_splice_bits(struct sk_buff * skb, struct sock * sk, unsigned int offset, struct pipe_inode_info * pipe, unsigned int tlen, unsigned int flags)
```

```json
{
  "name": "skb_splice_bits",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588463728,
      "name": "skb_splice_bits",
      "external": true,
      "loc": "net/core/skbuff.c:2425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp.c:tcp_splice_data_recv",
        "net/unix/af_unix.c:unix_stream_splice_actor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588463728,
      "name": "skb_splice_bits",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
<b>Param removed. </b>
<code>ssize_t (*)(struct sock *, struct pipe_inode_info *, struct splice_pipe_desc *) splice_cb</code>
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
