# Function: <code>packet_snd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587266403,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2634",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587731833,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2804",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587946585,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2758",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588104694,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2826",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588648038,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2815",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589003779,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2789",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589231100,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2796",
      "file": "net/packet/af_packet.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_sendmsg"
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589676384,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2820",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676384,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2462
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589900624,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589900624,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2462
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590932288,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2850",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590932288,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1899
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590996640,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2867",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590996640,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1859
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590927008,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2876",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590927008,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1859
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591763520,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2882",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591763520,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1889
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593475744,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2934",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593475744,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1968
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595396176,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2934",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595396176,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1961
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595791792,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2947",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595791792,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1980
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596642416,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2943",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596642416,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1999
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503631056,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503631056,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2136
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236267740,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236267740,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2276
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297449648,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297449648,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2844
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279575530,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279575530,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1866
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589504992,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589504992,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2462
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589231056,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589231056,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2462
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589946256,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589946256,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2462
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
```

```json
{
  "name": "packet_snd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589998592,
      "name": "packet_snd",
      "external": false,
      "loc": "net/packet/af_packet.c:2839",
      "file": "net/packet/af_packet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/packet/af_packet.c:packet_sendmsg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589998592,
      "name": "packet_snd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2472
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
int packet_snd(struct socket * sock, struct msghdr * msg, size_t len)
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
