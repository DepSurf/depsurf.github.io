# Function: <code>INET_ECN_set_ce</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588432555,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588638427,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589510976,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:174",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589510976,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589516576,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589516576,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 505
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589415040,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415040,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138848,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138848,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591700256,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591700256,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593490176,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593490176,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593956368,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593956368,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int INET_ECN_set_ce(struct sk_buff * skb)
```

```json
{
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594740064,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:172",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594740064,
      "name": "INET_ECN_set_ce",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502183600,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234931448,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295661520,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278438842,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588245163,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586655713,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "drivers/net/vxlan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/vxlan.c:vxlan_rcv",
        "drivers/net/vxlan.c:vxlan_rcv"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587957979,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588707845,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/ipv4/ip_tunnel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/ip_tunnel.c:ip_tunnel_rcv"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588576987,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
  "name": "INET_ECN_set_ce",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588714475,
      "name": "INET_ECN_set_ce",
      "external": false,
      "loc": "include/net/inet_ecn.h:143",
      "file": "net/core/filter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/filter.c:bpf_skb_ecn_set_ce"
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int INET_ECN_set_ce(struct sk_buff * skb)
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
