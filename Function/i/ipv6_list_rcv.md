# Function: <code>ipv6_list_rcv</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588911296,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:286",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588911296,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589353456,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:286",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589353456,
      "name": "ipv6_list_rcv",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589577584,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589577584,
      "name": "ipv6_list_rcv",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590582832,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:321",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590582832,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590643248,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:311",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590643248,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590570608,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:311",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590570608,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591382432,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:311",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591382432,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593057232,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:323",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593057232,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594949920,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:323",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594949920,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595342544,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:323",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595342544,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596183296,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:324",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596183296,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503252544,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503252544,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235925588,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235925588,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296996992,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296996992,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279280632,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279280632,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589181952,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181952,
      "name": "ipv6_list_rcv",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588906944,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588906944,
      "name": "ipv6_list_rcv",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589618816,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589618816,
      "name": "ipv6_list_rcv",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```

```json
{
  "name": "ipv6_list_rcv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589667248,
      "name": "ipv6_list_rcv",
      "external": true,
      "loc": "net/ipv6/ip6_input.c:298",
      "file": "net/ipv6/ip6_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netif_receive_skb_list_core",
        "net/core/dev.c:__netif_receive_skb_list_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589667248,
      "name": "ipv6_list_rcv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void ipv6_list_rcv(struct list_head * head, struct packet_type * pt, struct net_device * orig_dev)
```
</details>
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
