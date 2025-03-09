# Function: <code>tcp_v6_restore_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587175544,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1338",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
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
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587629715,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1358",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
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
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587834466,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1001",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587977968,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1022",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587977968,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588513888,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1030",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588513888,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878080,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1049",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878080,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589101376,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1053",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589101376,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589554608,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1082",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589554608,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589778640,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589778640,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590815908,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1170",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590799744,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590876024,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1191",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590858464,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590805162,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1218",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590787424,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591623492,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1221",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591605280,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593298272,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1172",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593298272,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595204032,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1186",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595204032,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595599760,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1184",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595599760,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596442752,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1336",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596442752,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503483688,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503483688,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236135624,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236135624,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297269600,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297269600,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279472118,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383008,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383008,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589108000,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589108000,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589819872,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589819872,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void tcp_v6_restore_cb(struct sk_buff * skb)
```

```json
{
  "name": "tcp_v6_restore_cb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589870800,
      "name": "tcp_v6_restore_cb",
      "external": false,
      "loc": "net/ipv6/tcp_ipv6.c:1104",
      "file": "net/ipv6/tcp_ipv6.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv",
        "net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589870800,
      "name": "tcp_v6_restore_cb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void tcp_v6_restore_cb(struct sk_buff * skb)
```
</details>
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
