# Function: <code>ndisc_recv_na</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587107406,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:876",
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587554368,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:904",
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
      "addr": 18446744071587554368,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587758992,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:924",
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
      "addr": 18446744071587758992,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 805
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587914800,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:924",
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
      "addr": 18446744071587914800,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 835
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588449888,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:937",
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
      "addr": 18446744071588449888,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 870
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:937",
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
      "addr": 18446744071588811216,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
    },
    {
      "addr": 18446744071588817247,
      "name": "ndisc_recv_na.cold.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:937",
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
      "addr": 18446744071589034128,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 797
    },
    {
      "addr": 18446744071589040127,
      "name": "ndisc_recv_na.cold.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:950",
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
      "addr": 18446744071589487328,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071589493513,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446744071589711200,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071589717353,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:952",
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
      "addr": 18446744071590725936,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
    },
    {
      "addr": 18446744071590736703,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:954",
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
      "addr": 18446744071590784848,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
    },
    {
      "addr": 18446744071591636540,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:954",
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
      "addr": 18446744071590711904,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    },
    {
      "addr": 18446744071591579965,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:954",
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
      "addr": 18446744071591528128,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 860
    },
    {
      "addr": 18446744071592740138,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:969",
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
      "addr": 18446744071593215808,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1137
    },
    {
      "addr": 18446744071594626805,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595115216,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:989",
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
      "addr": 18446744071595115216,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1228
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
enum skb_drop_reason ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595509248,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:991",
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
      "addr": 18446744071595509248,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1247
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
enum skb_drop_reason ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596352768,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:991",
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
      "addr": 18446744071596352768,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1258
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503402512,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446603336503402512,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236068604,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297177952,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 13835058055297177952,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279395536,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446743936279395536,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 588
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446744071589315568,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071589321721,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446744071589040560,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071589046713,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446744071589752432,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071589758585,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
```

```json
{
  "name": "ndisc_recv_na",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ndisc_recv_na",
      "external": false,
      "loc": "net/ipv6/ndisc.c:951",
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
      "addr": 18446744071589803088,
      "name": "ndisc_recv_na",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071589809268,
      "name": "ndisc_recv_na.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void ndisc_recv_na(struct sk_buff * skb)
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
void ndisc_recv_na(struct sk_buff * skb)
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
