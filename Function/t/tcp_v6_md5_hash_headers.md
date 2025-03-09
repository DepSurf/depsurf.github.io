# Function: <code>tcp_v6_md5_hash_headers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```

```json
{
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587616064,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:533",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587616064,
      "name": "tcp_v6_md5_hash_headers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```

```json
{
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587820928,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:542",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587820928,
      "name": "tcp_v6_md5_hash_headers",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```

```json
{
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587978160,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:565",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978160,
      "name": "tcp_v6_md5_hash_headers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
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
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```

```json
{
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588514128,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:567",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588514128,
      "name": "tcp_v6_md5_hash_headers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588880480,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:581",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880480,
      "name": "tcp_v6_md5_hash_headers.isra.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589103824,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:584",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103824,
      "name": "tcp_v6_md5_hash_headers.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589556816,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:591",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589556816,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589780848,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589780848,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590802208,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:636",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590802208,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590861600,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:647",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590861600,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590790480,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:662",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590790480,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591608048,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:665",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591608048,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593301344,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:669",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593301344,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595205376,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:676",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595205376,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595601184,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:673",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595601184,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596443456,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:693",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596443456,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503485800,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503485800,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```

```json
{
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236135928,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236135928,
      "name": "tcp_v6_md5_hash_headers",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297272736,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297272736,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279460820,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279460820,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589385216,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589385216,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589110208,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589110208,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589822080,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589822080,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "tcp_v6_md5_hash_headers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589873136,
      "name": "tcp_v6_md5_hash_headers",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:593",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_send_response",
        "net/ipv6/tcp_ipv6.c:tcp_v6_md5_hash_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589873136,
      "name": "tcp_v6_md5_hash_headers.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
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
int tcp_v6_md5_hash_headers(struct tcp_md5sig_pool * hp, const struct in6_addr * daddr, const struct in6_addr * saddr, const struct tcphdr * th, int nbytes)
```
</details>
</li>
</ul>
