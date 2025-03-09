# Function: <code>ipv6_srh_rcv</code>

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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587842728,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587999127,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:323",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
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
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588535719,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:356",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
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
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588900019,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:356",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
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
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589123498,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:356",
      "file": "net/ipv6/exthdrs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589575888,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589575888,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589800272,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589800272,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590823328,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:353",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590823328,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1277
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590883344,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:353",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590883344,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1283
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590812064,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590812064,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1592
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591630848,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:363",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591630848,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1592
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593324624,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:369",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593324624,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595230144,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:369",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595230144,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595626112,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:366",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595626112,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596473536,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:368",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596473536,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503506056,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503506056,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1432
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236157944,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236157944,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1952
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297297344,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297297344,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1840
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279477726,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279477726,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1316
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589404640,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404640,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129632,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129632,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589841504,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589841504,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
```

```json
{
  "name": "ipv6_srh_rcv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589892784,
      "name": "ipv6_srh_rcv",
      "external": false,
      "loc": "net/ipv6/exthdrs.c:352",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/exthdrs.c:ipv6_rthdr_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892784,
      "name": "ipv6_srh_rcv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1511
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
int ipv6_srh_rcv(struct sk_buff * skb)
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
