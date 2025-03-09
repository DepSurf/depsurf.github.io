# Function: <code>__netdev_alloc_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586234016,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:415",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:page_to_skb",
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586234016,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586658448,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:416",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:try_fill_recv",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658448,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586843328,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:416",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586843328,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951648,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:415",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951648,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587443280,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:386",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587443280,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587747568,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:386",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747568,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587881744,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:393",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587881744,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588186912,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588186912,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392064,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392064,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589253728,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:425",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589253728,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252896,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:430",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252896,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589147632,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:476",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/core/selftests.c:net_test_get_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589147632,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:478",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/core/selftests.c:net_test_get_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592694231,
      "name": "__netdev_alloc_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589867808,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:478",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/core/selftests.c:net_test_get_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594579764,
      "name": "__netdev_alloc_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591395168,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:614",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/core/selftests.c:net_test_get_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596321960,
      "name": "__netdev_alloc_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071593159952,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:698",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/core/selftests.c:net_test_get_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596851692,
      "name": "__netdev_alloc_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071593615200,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:699",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_decompress_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers",
        "net/core/selftests.c:net_test_get_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597776588,
      "name": "__netdev_alloc_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071594390400,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501907368,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/smsc/smc91x.c:smc_rcv",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501907368,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234668700,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234668700,
      "name": "__netdev_alloc_skb",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295319824,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295319824,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278220960,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278220960,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 374
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587998848,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587998848,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587711952,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587711952,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588330624,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588330624,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
struct sk_buff * __netdev_alloc_skb(struct net_device * dev, unsigned int len, gfp_t gfp_mask)
```

```json
{
  "name": "__netdev_alloc_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588466080,
      "name": "__netdev_alloc_skb",
      "external": true,
      "loc": "net/core/skbuff.c:424",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame",
        "drivers/net/xen-netfront.c:xennet_alloc_rx_buffers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588466080,
      "name": "__netdev_alloc_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
