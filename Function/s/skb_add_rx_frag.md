# Function: <code>skb_add_rx_frag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586206400,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:531",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586206400,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586627216,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:532",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586627216,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586812016,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:532",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586812016,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586936368,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:531",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936368,
      "name": "skb_add_rx_frag",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587429552,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:502",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587429552,
      "name": "skb_add_rx_frag",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587732112,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:502",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587732112,
      "name": "skb_add_rx_frag",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587866336,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:509",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587866336,
      "name": "skb_add_rx_frag",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588172784,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588172784,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588377984,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588377984,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589243536,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:542",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_fill_frags",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589243536,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242832,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:556",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_fill_frags",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242832,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589137808,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:603",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589137808,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589858672,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:605",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589858672,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591387184,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:605",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387184,
      "name": "skb_add_rx_frag",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593151920,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:765",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593151920,
      "name": "skb_add_rx_frag",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593606768,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:847",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593606768,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594381488,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:848",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:receive_mergeable",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/xdp/xsk.c:xsk_build_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594381488,
      "name": "skb_add_rx_frag",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501889080,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501889080,
      "name": "skb_add_rx_frag",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234651872,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234651872,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295298096,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295298096,
      "name": "skb_add_rx_frag",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278206838,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278206838,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587984768,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587984768,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697872,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697872,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588316544,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588316544,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void skb_add_rx_frag(struct sk_buff * skb, int i, struct page * page, int off, int size, unsigned int truesize)
```

```json
{
  "name": "skb_add_rx_frag",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588451680,
      "name": "skb_add_rx_frag",
      "external": true,
      "loc": "net/core/skbuff.c:543",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588451680,
      "name": "skb_add_rx_frag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
