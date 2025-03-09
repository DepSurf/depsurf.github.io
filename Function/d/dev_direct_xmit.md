# Function: <code>dev_direct_xmit</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587838384,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3612",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838384,
      "name": "dev_direct_xmit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587972048,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3907",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972048,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 442
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588285680,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3916",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588285680,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588491296,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588491296,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589363280,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:4174",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:xsk_generic_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589363280,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590990231,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:2887",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ],
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589553911,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:2954",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:__net_test_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590920657,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:2954",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590298583,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:2974",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:__net_test_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591756481,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:2974",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591882112,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3017",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:__net_test_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593465829,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3017",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593683664,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3042",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:__net_test_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595382677,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3042",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594164336,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3097",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:__net_test_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595784049,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3097",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_xmit"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594960895,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3178",
      "file": "net/core/selftests.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/selftests.c:__net_test_loopback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596634052,
      "name": "dev_direct_xmit",
      "external": false,
      "loc": "include/linux/netdevice.h:3178",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_xmit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502022176,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502022176,
      "name": "dev_direct_xmit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234774144,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234774144,
      "name": "dev_direct_xmit",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295464032,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295464032,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278312474,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278312474,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098080,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098080,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587810992,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587810992,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429856,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit",
        "net/xdp/xsk.c:__xsk_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429856,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```

```json
{
  "name": "dev_direct_xmit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566160,
      "name": "dev_direct_xmit",
      "external": true,
      "loc": "net/core/dev.c:3816",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566160,
      "name": "dev_direct_xmit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int dev_direct_xmit(struct sk_buff * skb, u16 queue_id)
```
</details>
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
