# Function: <code>tcp_v6_get_syncookie</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795168,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795168,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590817360,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1139",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590817360,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590877456,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1155",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590877456,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590806576,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1182",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590806576,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591624944,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1185",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591624944,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593317584,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1136",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593317584,
      "name": "tcp_v6_get_syncookie",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595222464,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1150",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595222464,
      "name": "tcp_v6_get_syncookie",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595618432,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1148",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595618432,
      "name": "tcp_v6_get_syncookie",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596465552,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1300",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596465552,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 245
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503500248,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503500248,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236152440,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236152440,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297290352,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297290352,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279473180,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279473180,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399536,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399536,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589124528,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124528,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836400,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836400,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
```

```json
{
  "name": "tcp_v6_get_syncookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589887680,
      "name": "tcp_v6_get_syncookie",
      "external": true,
      "loc": "net/ipv6/tcp_ipv6.c:1073",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_tcp_gen_syncookie"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589887680,
      "name": "tcp_v6_get_syncookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
u16 tcp_v6_get_syncookie(struct sock * sk, struct ipv6hdr * iph, struct tcphdr * th, u32 * cookie)
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
