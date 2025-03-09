# Function: <code>udp_unicast_rcv_skb</code>

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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588406400,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2134",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588406400,
      "name": "udp_unicast_rcv_skb.isra.53",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588598400,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2236",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588598400,
      "name": "udp_unicast_rcv_skb.isra.63",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589009968,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2222",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589009968,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589234608,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589234608,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590210304,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2266",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590210304,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590260960,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2319",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590260960,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590174768,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2370",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590174768,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590955504,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2382",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590955504,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592595632,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2391",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592595632,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594459584,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2393",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594459584,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594850864,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2365",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594850864,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595661728,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2338",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595661728,
      "name": "udp_unicast_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502860904,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502860904,
      "name": "udp_unicast_rcv_skb.isra.0",
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235559188,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235559188,
      "name": "udp_unicast_rcv_skb",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296513568,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296513568,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278965584,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278965584,
      "name": "udp_unicast_rcv_skb.isra.0",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588840992,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588840992,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588552928,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588552928,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589277168,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589277168,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
  "name": "udp_unicast_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589319424,
      "name": "udp_unicast_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv4/udp.c:__udp4_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589319424,
      "name": "udp_unicast_rcv_skb.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
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
int udp_unicast_rcv_skb(struct sock * sk, struct sk_buff * skb, struct udphdr * uh)
```
</details>
</li>
</ul>
