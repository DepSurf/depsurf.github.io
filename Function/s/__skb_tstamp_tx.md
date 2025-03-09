# Function: <code>__skb_tstamp_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586213664,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:3762",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213664,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586639184,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:3803",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586639184,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586824720,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:3838",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586824720,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 321
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586958976,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:3926",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586958976,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587451184,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4314",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587451184,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587754944,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4353",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754944,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587889552,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4373",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587889552,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588195232,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4558",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588195232,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588400400,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400400,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261312,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4672",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261312,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260448,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4739",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260448,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, const struct sk_buff * ack_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589163872,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4825",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589163872,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, const struct sk_buff * ack_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589878688,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4893",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589878688,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 501
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, const struct sk_buff * ack_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591402944,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4808",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591402944,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 581
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, const struct sk_buff * ack_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593168016,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:5010",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593168016,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, const struct sk_buff * ack_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593631120,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:5201",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593631120,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, const struct sk_buff * ack_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594406704,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:5330",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594406704,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 665
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501916672,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501916672,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234676976,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234676976,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295332144,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295332144,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 632
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278228792,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278228792,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 342
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588007184,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588007184,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587720272,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720272,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588338960,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588338960,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void __skb_tstamp_tx(struct sk_buff * orig_skb, struct skb_shared_hwtstamps * hwtstamps, struct sock * sk, int tstype)
```

```json
{
  "name": "__skb_tstamp_tx",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588474432,
      "name": "__skb_tstamp_tx",
      "external": true,
      "loc": "net/core/skbuff.c:4570",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_tstamp_tx",
        "net/core/dev.c:__dev_queue_xmit",
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588474432,
      "name": "__skb_tstamp_tx",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sk_buff * ack_skb</code>
</li>
<li>
<b>Param reordered. </b>
<code>orig_skb, hwtstamps, sk, tstype</code> ➡️ <code>orig_skb, ack_skb, hwtstamps, sk, tstype</code>
</li>
</ul>
</details>
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
