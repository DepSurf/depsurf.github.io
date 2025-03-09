# Function: <code>__udp4_lib_err_encap</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588600479,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:595",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589012153,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589236825,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sock * __udp4_lib_err_encap(struct net * net, const struct iphdr * iph, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, u32 info)
```

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590198080,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:588",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590198080,
      "name": "__udp4_lib_err_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
struct sock * __udp4_lib_err_encap(struct net * net, const struct iphdr * iph, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, u32 info)
```

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590247504,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:638",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590247504,
      "name": "__udp4_lib_err_encap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 299
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
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590177022,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:644",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590957771,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:645",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592600699,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:645",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594464539,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:653",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594855665,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:668",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595666755,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:638",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502864292,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235560544,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296520512,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278967650,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588843209,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588555145,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589279385,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp4_lib_err_encap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589320793,
      "name": "__udp4_lib_err_encap",
      "external": false,
      "loc": "net/ipv4/udp.c:582",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_err"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sock * __udp4_lib_err_encap(struct net * net, const struct iphdr * iph, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, u32 info)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct sock * __udp4_lib_err_encap(struct net * net, const struct iphdr * iph, struct udphdr * uh, struct udp_table * udptable, struct sk_buff * skb, u32 info)
```
</details>
</li>
</ul>
