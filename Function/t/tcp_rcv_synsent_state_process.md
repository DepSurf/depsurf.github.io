# Function: <code>tcp_rcv_synsent_state_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586657887,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5517",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587103965,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5582",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587301571,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5668",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587432612,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5656",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587953968,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5562",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588304011,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5723",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588492849,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5772",
      "file": "net/ipv4/tcp_input.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588900768,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5818",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588900768,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2111
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589124896,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124896,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2119
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590092016,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5915",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590092016,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1851
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138160,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6051",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138160,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1852
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590052704,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6057",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590052704,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1816
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6092",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590826384,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1833
    },
    {
      "addr": 18446744071592717675,
      "name": "tcp_rcv_synsent_state_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6158",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592461888,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1749
    },
    {
      "addr": 18446744071594604057,
      "name": "tcp_rcv_synsent_state_process.cold",
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6180",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594316272,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1745
    },
    {
      "addr": 18446744071596339345,
      "name": "tcp_rcv_synsent_state_process.cold",
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6187",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594702672,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1746
    },
    {
      "addr": 18446744071596868736,
      "name": "tcp_rcv_synsent_state_process.cold",
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:6334",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595507216,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1787
    },
    {
      "addr": 18446744071597792870,
      "name": "tcp_rcv_synsent_state_process.cold",
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502740648,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502740648,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1788
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235444824,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235444824,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1964
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296365312,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296365312,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2304
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278865494,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278865494,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1736
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588731280,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588731280,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2119
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588443264,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588443264,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2119
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589167456,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589167456,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2119
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
```

```json
{
  "name": "tcp_rcv_synsent_state_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589207456,
      "name": "tcp_rcv_synsent_state_process",
      "external": false,
      "loc": "net/ipv4/tcp_input.c:5869",
      "file": "net/ipv4/tcp_input.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_input.c:tcp_rcv_state_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589207456,
      "name": "tcp_rcv_synsent_state_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2142
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
int tcp_rcv_synsent_state_process(struct sock * sk, struct sk_buff * skb, const struct tcphdr * th)
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
