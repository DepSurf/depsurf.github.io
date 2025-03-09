# Function: <code>skb_clone_tx_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:2983",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3190",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3190",
      "file": "drivers/net/virtio_net.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3242",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3316",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3316",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3500",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3500",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588048112,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:35",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588048112,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588216384,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:35",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216384,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588550432,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588550432,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767280,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588767280,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589639072,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589639072,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589662656,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589662656,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589554240,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589554240,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590299024,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590299024,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591882816,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591882816,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593684448,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593684448,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594165120,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594165120,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594961680,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/virtio_net.c:start_xmit",
        "drivers/net/xen-netfront.c:xennet_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594961680,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502332448,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502332448,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235072756,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_start_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235072756,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295851392,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295851392,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278555078,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278555078,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3771",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3771",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3771",
      "file": "drivers/net/loopback.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "skb_clone_tx_timestamp",
      "external": false,
      "loc": "include/linux/skbuff.h:3771",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588705840,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588705840,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```

```json
{
  "name": "skb_clone_tx_timestamp",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588845760,
      "name": "skb_clone_tx_timestamp",
      "external": true,
      "loc": "net/core/timestamping.c:22",
      "file": "net/core/timestamping.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/loopback.c:loopback_xmit",
        "drivers/net/tun.c:tun_net_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588845760,
      "name": "skb_clone_tx_timestamp",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void skb_clone_tx_timestamp(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
