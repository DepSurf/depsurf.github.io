# Function: <code>udp6_unicast_rcv_skb</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588826592,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:754",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588826592,
      "name": "udp6_unicast_rcv_skb.isra.24",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589049712,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:836",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589049712,
      "name": "udp6_unicast_rcv_skb.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589503328,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589503328,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589727408,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589727408,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590747072,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:826",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590747072,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590806048,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:880",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590806048,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590733168,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:893",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590733168,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591546688,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:895",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591546688,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593236496,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:897",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593236496,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595137168,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:927",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595137168,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595526496,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:943",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595526496,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596373184,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:913",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596373184,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503421200,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503421200,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236077396,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236077396,
      "name": "udp6_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297197648,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297197648,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279408812,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279408812,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589331776,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589331776,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589056768,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589056768,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589768640,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589768640,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
  "name": "udp6_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589819344,
      "name": "udp6_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv6/udp.c:824",
      "file": "net/ipv6/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/udp.c:__udp6_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589819344,
      "name": "udp6_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int udp6_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```
</details>
</li>
</ul>
