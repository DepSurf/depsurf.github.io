# Function: <code>tcp_small_queue_check</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool tcp_small_queue_check(struct sock * sk, const struct sk_buff * skb, unsigned int factor)
```

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305312,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2085",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305312,
      "name": "tcp_small_queue_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool tcp_small_queue_check(struct sock * sk, const struct sk_buff * skb, unsigned int factor)
```

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587437008,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2171",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587437008,
      "name": "tcp_small_queue_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587960816,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2222",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587960816,
      "name": "tcp_small_queue_check.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588309568,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2205",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309568,
      "name": "tcp_small_queue_check.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588498752,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2228",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588498752,
      "name": "tcp_small_queue_check.isra.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588907776,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2244",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588907776,
      "name": "tcp_small_queue_check.isra.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589131824,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131824,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590100704,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2326",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590100704,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590147168,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2496",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590147168,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590061184,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2497",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590061184,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2497",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590834944,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
    },
    {
      "addr": 18446744071592718036,
      "name": "tcp_small_queue_check.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2497",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592470912,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071594604459,
      "name": "tcp_small_queue_check.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2499",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594326176,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071596339773,
      "name": "tcp_small_queue_check.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2541",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594711776,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    },
    {
      "addr": 18446744071596869125,
      "name": "tcp_small_queue_check.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2597",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595514480,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    },
    {
      "addr": 18446744071597793025,
      "name": "tcp_small_queue_check.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502747560,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502747560,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
bool tcp_small_queue_check(struct sock * sk, const struct sk_buff * skb, unsigned int factor)
```

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235449836,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235449836,
      "name": "tcp_small_queue_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296373824,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296373824,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278872012,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278872012,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588738208,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738208,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588450160,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450160,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589174384,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174384,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_small_queue_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589214416,
      "name": "tcp_small_queue_check",
      "external": false,
      "loc": "net/ipv4/tcp_output.c:2263",
      "file": "net/ipv4/tcp_output.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_output.c:tcp_write_xmit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589214416,
      "name": "tcp_small_queue_check.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool tcp_small_queue_check(struct sock * sk, const struct sk_buff * skb, unsigned int factor)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
bool tcp_small_queue_check(struct sock * sk, const struct sk_buff * skb, unsigned int factor)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool tcp_small_queue_check(struct sock * sk, const struct sk_buff * skb, unsigned int factor)
```
</details>
</li>
</ul>
