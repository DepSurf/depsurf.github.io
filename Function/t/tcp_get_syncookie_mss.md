# Function: <code>tcp_get_syncookie_mss</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589090208,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589090208,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590058537,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6585",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590096078,
      "name": "tcp_get_syncookie_mss.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071590058352,
      "name": "tcp_get_syncookie_mss",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590103529,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6735",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591634598,
      "name": "tcp_get_syncookie_mss.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071590103344,
      "name": "tcp_get_syncookie_mss",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590012640,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6744",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012640,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590783696,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6779",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590783696,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592415472,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6865",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592415472,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594267360,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6895",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594267360,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594653456,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6902",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594653456,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595457520,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:7062",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595457520,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502711168,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502711168,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235409484,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235409484,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296321296,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296321296,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278835312,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278835312,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588696592,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588696592,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588408576,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588408576,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589132768,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589132768,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```

```json
{
  "name": "tcp_get_syncookie_mss",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589172592,
      "name": "tcp_get_syncookie_mss",
      "external": true,
      "loc": "net/ipv4/tcp_input.c:6526",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_ipv4.c:tcp_v4_get_syncookie",
        "net/ipv6/tcp_ipv6.c:tcp_v6_get_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589172592,
      "name": "tcp_get_syncookie_mss",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
u16 tcp_get_syncookie_mss(struct request_sock_ops * rsk_ops, const struct tcp_request_sock_ops * af_ops, struct sock * sk, struct tcphdr * th)
```
</details>
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
