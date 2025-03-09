# Function: <code>ndisc_recv_rs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587107684,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:980",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_rcv"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587555184,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1018",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587555184,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587759808,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1038",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587759808,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587915648,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1038",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587915648,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
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
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588450768,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1051",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588450768,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1051",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588812032,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
    },
    {
      "addr": 18446744071588817309,
      "name": "ndisc_recv_rs.cold.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1051",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589034928,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589040189,
      "name": "ndisc_recv_rs.cold.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1064",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589488160,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589493578,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589712032,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589717418,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1066",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590726784,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071590736768,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1068",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590785696,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
    },
    {
      "addr": 18446744071591636605,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1068",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590712768,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
    },
    {
      "addr": 18446744071591580030,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1068",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591528992,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 490
    },
    {
      "addr": 18446744071592740203,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1109",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593216960,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    },
    {
      "addr": 18446744071594626865,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595116464,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1129",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595116464,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
enum skb_drop_reason ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595510512,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1130",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595510512,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
enum skb_drop_reason ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596354048,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1130",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596354048,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 566
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
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503403280,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503403280,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236068244,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ndisc.c:ndisc_rcv"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297179040,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297179040,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
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
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279396124,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279396124,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589316400,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589321786,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589041392,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589046778,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589753264,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589758650,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_rs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_rs",
      "external": false,
      "loc": "net/ipv6/ndisc.c:1065",
      "file": "net/ipv6/ndisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ndisc.c:ndisc_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589803920,
      "name": "ndisc_recv_rs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
    },
    {
      "addr": 18446744071589809333,
      "name": "ndisc_recv_rs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void ndisc_recv_rs(struct sk_buff * skb)
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
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>enum skb_drop_reason</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void ndisc_recv_rs(struct sk_buff * skb)
```
</details>
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
