# Function: <code>packet_pick_tx_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void packet_pick_tx_queue(struct net_device * dev, struct sk_buff * skb)
```

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587247776,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:320",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:tpacket_snd",
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587247776,
      "name": "packet_pick_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void packet_pick_tx_queue(struct net_device * dev, struct sk_buff * skb)
```

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587710816,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:321",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587710816,
      "name": "packet_pick_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
void packet_pick_tx_queue(struct net_device * dev, struct sk_buff * skb)
```

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587925328,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:320",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg",
        "net/packet/af_packet.c:tpacket_snd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587925328,
      "name": "packet_pick_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588083929,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:320",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588628553,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:315",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588993829,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:283",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589217461,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:284",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589672037,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589896277,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
u16 packet_pick_tx_queue(struct sk_buff * skb)
```

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590926096,
      "name": "packet_pick_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071590953437,
      "name": "packet_pick_tx_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
u16 packet_pick_tx_queue(struct sk_buff * skb)
```

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:276",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_direct_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590990080,
      "name": "packet_pick_tx_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    },
    {
      "addr": 18446744071591637430,
      "name": "packet_pick_tx_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590920565,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:276",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591756389,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:277",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593465749,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:313",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595382597,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:313",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595783972,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:311",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596633984,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:311",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503621276,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236263688,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297434936,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279570516,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589500645,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589226709,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589941909,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_pick_tx_queue",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589992117,
      "name": "packet_pick_tx_queue",
      "external": false,
      "loc": "net/packet/af_packet.c:272",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void packet_pick_tx_queue(struct net_device * dev, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u16 packet_pick_tx_queue(struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
u16 packet_pick_tx_queue(struct sk_buff * skb)
```
</details>
</li>
</ul>
