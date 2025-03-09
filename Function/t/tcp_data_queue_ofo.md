# Function: <code>tcp_data_queue_ofo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586644039,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4341",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587098249,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4405",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587295780,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4429",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587426651,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4388",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587949330,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4365",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588299787,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4465",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588488590,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4482",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588895120,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4495",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588895120,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1659
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589119200,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589119200,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1701
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590065040,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4574",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590065040,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1910
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590113360,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4712",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590113360,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1910
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590024544,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4722",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590024544,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1395
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4756",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590795456,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1421
    },
    {
      "addr": 18446744071592716663,
      "name": "tcp_data_queue_ofo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4775",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592433424,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071594603155,
      "name": "tcp_data_queue_ofo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4788",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594287376,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1577
    },
    {
      "addr": 18446744071596338471,
      "name": "tcp_data_queue_ofo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4793",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594673456,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1692
    },
    {
      "addr": 18446744071596867965,
      "name": "tcp_data_queue_ofo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4924",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595474208,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1772
    },
    {
      "addr": 18446744071597792372,
      "name": "tcp_data_queue_ofo.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502735144,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502735144,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1584
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235439124,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235439124,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1632
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296358416,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296358416,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2024
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278860540,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278860540,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1474
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588725584,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588725584,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1701
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588437568,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588437568,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1701
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589161760,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589161760,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1701
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
```

```json
{
  "name": "tcp_data_queue_ofo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589201728,
      "name": "tcp_data_queue_ofo",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:4545",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_data_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589201728,
      "name": "tcp_data_queue_ofo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1701
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
void tcp_data_queue_ofo(struct sock * sk, struct sk_buff * skb)
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
