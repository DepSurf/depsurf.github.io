# Function: <code>tcp_sacktag_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, const struct skb_mstamp * xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586628240,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1153",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shifted_skb",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586628240,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, const struct skb_mstamp * xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068736,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1155",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068736,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, const struct skb_mstamp * xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587265248,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1197",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587265248,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587402816,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1203",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587402816,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 593
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587923792,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1172",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923792,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 541
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588272688,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1199",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588272688,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588461344,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1185",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588461344,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 567
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588867536,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1195",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588867536,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589091136,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589091136,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590051808,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1200",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590051808,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590097008,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1305",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097008,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590010928,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1305",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590010928,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590781968,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1337",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590781968,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592416976,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1346",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592416976,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594270432,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1345",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594270432,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594656512,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1344",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594656512,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595460576,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595460576,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502705656,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502705656,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235404348,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235404348,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 584
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296324336,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296324336,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278837574,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278837574,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588697520,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588697520,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588409504,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588409504,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589133696,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589133696,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
u8 tcp_sacktag_one(struct sock * sk, struct tcp_sacktag_state * state, u8 sacked, u32 start_seq, u32 end_seq, int dup_sack, int pcount, u64 xmit_time)
```

```json
{
  "name": "tcp_sacktag_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589173520,
      "name": "tcp_sacktag_one",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:1198",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_shifted_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173520,
      "name": "tcp_sacktag_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct skb_mstamp * xmit_time</code> ➡️ <code>u64 xmit_time</code>
</li>
</ul>
</details>
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
