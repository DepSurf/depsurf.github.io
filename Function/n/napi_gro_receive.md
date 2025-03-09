# Function: <code>napi_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586297696,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:4362",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586297696,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725904,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:4637",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725904,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586911776,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:4660",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586911776,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587043280,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:4882",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587043280,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543568,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5023",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587543568,
      "name": "napi_gro_receive",
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587847568,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5153",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587847568,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587986144,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5689",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587986144,
      "name": "napi_gro_receive",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588297040,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5699",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588297040,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588505360,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588505360,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376832,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:6005",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_receive",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376832,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589382640,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:6106",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_receive",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589382640,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589278272,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:6225",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589278272,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590005664,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:6207",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590005664,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 483
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591773952,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/gro.c:629",
      "file": "net/core/gro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591773952,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593565824,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/gro.c:646",
      "file": "net/core/gro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593565824,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 515
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594034768,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/gro.c:600",
      "file": "net/core/gro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594034768,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594822048,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/gro.c:600",
      "file": "net/core/gro.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/virtio_net.c:receive_buf",
        "drivers/net/xen-netfront.c:handle_incoming_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594822048,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 545
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502037864,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502037864,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234787920,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234787920,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295483984,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295483984,
      "name": "napi_gro_receive",
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278325644,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278325644,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588112096,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588112096,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587824928,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587824928,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588443920,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588443920,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
gro_result_t napi_gro_receive(struct napi_struct * napi, struct sk_buff * skb)
```

```json
{
  "name": "napi_gro_receive",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588580736,
      "name": "napi_gro_receive",
      "external": true,
      "loc": "net/core/dev.c:5622",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_napi_poll",
        "drivers/net/xen-netfront.c:xennet_poll",
        "net/core/gro_cells.c:gro_cell_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580736,
      "name": "napi_gro_receive",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
