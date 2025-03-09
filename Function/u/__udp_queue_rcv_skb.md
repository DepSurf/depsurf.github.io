# Function: <code>__udp_queue_rcv_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586737952,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1463",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586737952,
      "name": "__udp_queue_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 301
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
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185136,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1454",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185136,
      "name": "__udp_queue_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587396848,
      "name": "__udp_queue_rcv_skb",
      "external": true,
      "loc": "net/ipv4/udp.c:1626",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_queue_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587396848,
      "name": "__udp_queue_rcv_skb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587531138,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1777",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_skb"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588053930,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1784",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_skb"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588405902,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1867",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_skb"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588597472,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1939",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589009048,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1925",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589233660,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590208321,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1970",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590258304,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2020",
      "file": "net/ipv4/udp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590258304,
      "name": "__udp_queue_rcv_skb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590172744,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2069",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590953509,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2081",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592593436,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2080",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594457125,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2082",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594848406,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2054",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595659263,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:2025",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502859844,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235557744,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296512276,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278964290,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588840044,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588551980,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589276220,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
  "name": "__udp_queue_rcv_skb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589318460,
      "name": "__udp_queue_rcv_skb",
      "external": false,
      "loc": "net/ipv4/udp.c:1961",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:udp_queue_rcv_one_skb"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int __udp_queue_rcv_skb(struct sock * sk, struct sk_buff * skb)
```
</details>
</li>
</ul>
