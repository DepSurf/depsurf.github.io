# Function: <code>__tcp_retransmit_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586677760,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2555",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586677760,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1437
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587124320,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2594",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587124320,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1661
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322096,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2714",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322096,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1645
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587454128,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2789",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587454128,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1640
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587975840,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2838",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587975840,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1757
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588325712,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2813",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588325712,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1979
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588514800,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2843",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514800,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1961
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588924976,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2870",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588924976,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2124
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589148912,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589148912,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590118528,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2966",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118528,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1340
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590166240,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3138",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590166240,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1350
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590080800,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3143",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590080800,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1275
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3143",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592719157,
      "name": "__tcp_retransmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071590855440,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1285
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3139",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594605596,
      "name": "__tcp_retransmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    },
    {
      "addr": 18446744071592491520,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1397
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3141",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596340884,
      "name": "__tcp_retransmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071594346864,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1347
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3223",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596870255,
      "name": "__tcp_retransmit_skb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071594734736,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595541440,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:3281",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595540096,
      "name": "__tcp_retransmit_skb.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1319
    },
    {
      "addr": 18446744071597793859,
      "name": "__tcp_retransmit_skb.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071595541440,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502764592,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502764592,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2064
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235469172,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235469172,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2200
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296395520,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296395520,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2816
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278887048,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278887048,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1818
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588755296,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588755296,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588467248,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588467248,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589191472,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589191472,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2139
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
int __tcp_retransmit_skb(struct sock * sk, struct sk_buff * skb, int segs)
```

```json
{
  "name": "__tcp_retransmit_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231536,
      "name": "__tcp_retransmit_skb",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:2897",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process",
        "net/ipv4/tcp_output.c:tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_send_loss_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231536,
      "name": "__tcp_retransmit_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2164
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int segs</code>
</li>
</ul>
</details>
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
