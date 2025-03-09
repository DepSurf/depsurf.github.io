# Function: <code>prb_dispatch_next_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587246270,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:916",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired",
        "net/packet/af_packet.c:tpacket_rcv"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587722984,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:916",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587933944,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:915",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588102632,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:923",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588645947,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:911",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588997072,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:887",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588997072,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221296,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:888",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221296,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589671216,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:880",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589671216,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589895456,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589895456,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590930716,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:882",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:__packet_lookup_frame_in_block",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590994508,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:886",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:__packet_lookup_frame_in_block",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590935992,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:887",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591783814,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:888",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593484635,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:924",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595402923,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:924",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595798577,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:926",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596649272,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:926",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503618456,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503618456,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236263048,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236263048,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297433920,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297433920,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279569718,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279569718,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589499824,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589499824,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589225888,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589225888,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589941088,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589941088,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
```

```json
{
  "name": "prb_dispatch_next_block",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589990960,
      "name": "prb_dispatch_next_block",
      "external": false,
      "loc": "net/packet/af_packet.c:881",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_rcv",
        "net/packet/af_packet.c:prb_retire_rx_blk_timer_expired"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990960,
      "name": "prb_dispatch_next_block",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void * prb_dispatch_next_block(struct tpacket_kbdq_core * pkc, struct packet_sock * po)
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
