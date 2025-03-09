# Function: <code>udp_sk_rx_dst_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586751538,
      "name": "udp_sk_rx_dst_set",
      "external": false,
      "loc": "net/ipv4/udp.c:1654",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
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
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587199233,
      "name": "udp_sk_rx_dst_set",
      "external": false,
      "loc": "net/ipv4/udp.c:1620",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
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
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587399657,
      "name": "udp_sk_rx_dst_set",
      "external": false,
      "loc": "net/ipv4/udp.c:1776",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/udp.c:__udp4_lib_rcv"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587524544,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:1935",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524544,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588047392,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:1934",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588047392,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588398064,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2017",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588398064,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588587968,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2103",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588587968,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589001264,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2089",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589001264,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589225664,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589225664,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590193360,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2133",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590193360,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590242688,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2186",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242688,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590156416,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2237",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590156416,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590936816,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2249",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590936816,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592579904,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2258",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592579904,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594441456,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2260",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594441456,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594831664,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2232",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594831664,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595643536,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2205",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595643536,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502843728,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502843728,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235552624,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235552624,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296499632,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296499632,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278955198,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278955198,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588832048,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588832048,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588543984,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588543984,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589268224,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589268224,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
```

```json
{
  "name": "udp_sk_rx_dst_set",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589315408,
      "name": "udp_sk_rx_dst_set",
      "external": true,
      "loc": "net/ipv4/udp.c:2125",
      "file": "net/ipv4/udp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/udp.c:__udp4_lib_rcv",
        "net/ipv6/udp.c:__udp6_lib_rcv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589315408,
      "name": "udp_sk_rx_dst_set",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool udp_sk_rx_dst_set(struct sock * sk, struct dst_entry * dst)
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
