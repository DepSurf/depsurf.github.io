# Function: <code>tcp_skb_shift</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588869646,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1375",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588883440,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589094222,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589107520,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590075083,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1380",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590074656,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590121005,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1486",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590120576,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590034910,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1486",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590034480,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590806061,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1518",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_collapse_retrans"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590805616,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592440795,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1527",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592440240,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594294891,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594294320,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594681072,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1525",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594680496,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595485888,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1559",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_shift_skb_data",
        "net/ipv4/tcp_output.c:tcp_retrans_try_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595485312,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502713380,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502724176,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235422820,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235427788,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296327188,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296344608,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278838912,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278851366,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588700606,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713904,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588412590,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588425888,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589136782,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150080,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```

```json
{
  "name": "tcp_skb_shift",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589176606,
      "name": "tcp_skb_shift",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:1378",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_sacktag_walk",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ],
      "caller_func": [
        "net/ipv4/tcp_output.c:__tcp_retransmit_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189984,
      "name": "tcp_skb_shift",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int tcp_skb_shift(struct sk_buff * to, struct sk_buff * from, int pcount, int shiftlen)
```
</details>
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
