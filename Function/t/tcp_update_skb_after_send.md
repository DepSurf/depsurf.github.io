# Function: <code>tcp_update_skb_after_send</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587977294,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1017",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:tcp_transmit_skb"
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
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588327574,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1013",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:tcp_write_xmit",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588496608,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:978",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588496608,
      "name": "tcp_update_skb_after_send",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588905328,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:978",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588905328,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129024,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129024,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590096144,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1045",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590096144,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590142128,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1199",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590142128,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590056624,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1199",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590056624,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590830352,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1199",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590830352,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592465744,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1198",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592465744,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594320160,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1195",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594320160,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594706576,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1197",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594706576,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595511024,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:1242",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595511024,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502744384,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502744384,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235449172,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235449172,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296369792,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296369792,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278868936,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278868936,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588735408,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588735408,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588447392,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588447392,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589171584,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589171584,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
```

```json
{
  "name": "tcp_update_skb_after_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589211616,
      "name": "tcp_update_skb_after_send",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:982",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb",
        "net/ipv4/tcp_output.c:__tcp_transmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211616,
      "name": "tcp_update_skb_after_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void tcp_update_skb_after_send(struct sock * sk, struct sk_buff * skb, u64 prior_wstamp)
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
