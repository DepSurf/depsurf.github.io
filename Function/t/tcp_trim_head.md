# Function: <code>tcp_trim_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586666144,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1262",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586666144,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587112400,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1277",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587112400,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587310640,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1299",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587310640,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587442304,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1374",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587442304,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587963648,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1428",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587963648,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588313104,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1419",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588313104,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588502192,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1407",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588502192,
      "name": "tcp_trim_head",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588912688,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1421",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588912688,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589136448,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589136448,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590107680,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1503",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_tso_acked",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590107680,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590155008,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1671",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_tso_acked",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590155008,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590068752,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1671",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068752,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590842560,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1671",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590842560,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592478048,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1666",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592478048,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594333776,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1663",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594333776,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594720336,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1657",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594720336,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595525056,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1718",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595525056,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502752296,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502752296,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235456564,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235456564,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296379936,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296379936,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278876222,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278876222,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588742832,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742832,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588454784,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588454784,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589179008,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589179008,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int tcp_trim_head(struct sock * sk, struct sk_buff * skb, u32 len)
```

```json
{
  "name": "tcp_trim_head",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589219072,
      "name": "tcp_trim_head",
      "external": true,
      "loc": "net/ipv4/tcp_output.c:1440",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_clean_rtx_queue",
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589219072,
      "name": "tcp_trim_head",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
