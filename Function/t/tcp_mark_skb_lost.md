# Function: <code>tcp_mark_skb_lost</code>

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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588376000,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588376000,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566432,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566432,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977568,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977568,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589202016,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589202016,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590174568,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_timeout_mark_lost"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590174672,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590119440,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1045",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_timeout_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590119440,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590033104,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1045",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590033104,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590804240,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1077",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590804240,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592438768,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1086",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592438768,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594292784,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1085",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594292784,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594678960,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1084",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594678960,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595483776,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1118",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_fastopen_synack",
        "net/ipv4/tcp_input.c:tcp_simple_retransmit",
        "net/ipv4/tcp_input.c:tcp_mark_head_lost",
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595483776,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502822368,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502822368,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235524120,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235524120,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296470352,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296470352,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278936114,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278936114,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588808400,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588808400,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588520336,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588520336,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589244576,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589244576,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_mark_skb_lost",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589285152,
      "name": "tcp_mark_skb_lost",
      "external": true,
      "loc": "net/ipv4/tcp_recovery.c:5",
      "file": "net/ipv4/tcp_recovery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_enter_loss",
        "net/ipv4/tcp_recovery.c:tcp_rack_detect_loss"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589285152,
      "name": "tcp_mark_skb_lost",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void tcp_mark_skb_lost(struct sock * sk, struct sk_buff * skb)
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
