# Function: <code>sock_queue_err_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586210160,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:3629",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210160,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586630512,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:3670",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586630512,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586815296,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:3696",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586815296,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586943648,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:3775",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586943648,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587437488,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4159",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587437488,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587741792,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4198",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741792,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587875008,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4218",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875008,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588182208,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4403",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182208,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588388000,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588388000,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589246608,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4517",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589246608,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245872,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4584",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245872,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589140672,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4670",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589140672,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589860496,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4738",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860496,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591383392,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4654",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591383392,
      "name": "sock_queue_err_skb",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593145984,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4856",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593145984,
      "name": "sock_queue_err_skb",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593599600,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:5047",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593599600,
      "name": "sock_queue_err_skb",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594374192,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:5173",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594374192,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 399
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501903264,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501903264,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234663328,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234663328,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295297200,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295297200,
      "name": "sock_queue_err_skb",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278216816,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278216816,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587994784,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587994784,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587707888,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587707888,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588326560,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326560,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int sock_queue_err_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "sock_queue_err_skb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588461984,
      "name": "sock_queue_err_skb",
      "external": true,
      "loc": "net/core/skbuff.c:4415",
      "file": "net/core/skbuff.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/skbuff.c:skb_complete_wifi_ack",
        "net/core/skbuff.c:__skb_complete_tx_timestamp",
        "net/ipv4/ip_sockglue.c:ip_local_error",
        "net/ipv4/ip_sockglue.c:ip_icmp_error",
        "net/ipv6/datagram.c:ipv6_local_error",
        "net/ipv6/datagram.c:ipv6_icmp_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461984,
      "name": "sock_queue_err_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
