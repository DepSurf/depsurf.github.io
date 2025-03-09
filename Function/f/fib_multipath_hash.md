# Function: <code>fib_multipath_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586535793,
      "name": "fib_multipath_hash",
      "external": false,
      "loc": "include/net/ip_fib.h:327",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586767320,
      "name": "fib_multipath_hash",
      "external": false,
      "loc": "include/net/ip_fib.h:327",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_route_lookup"
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
  "name": "fib_multipath_hash",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586978593,
      "name": "fib_multipath_hash",
      "external": false,
      "loc": "include/net/ip_fib.h:328",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587215317,
      "name": "fib_multipath_hash",
      "external": false,
      "loc": "include/net/ip_fib.h:328",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_route_lookup"
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
  "name": "fib_multipath_hash",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587176721,
      "name": "fib_multipath_hash",
      "external": false,
      "loc": "include/net/ip_fib.h:369",
      "file": "net/ipv4/route.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref",
        "net/ipv4/route.c:ip_route_input_noref"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587415714,
      "name": "fib_multipath_hash",
      "external": false,
      "loc": "include/net/ip_fib.h:369",
      "file": "net/ipv4/icmp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/icmp.c:icmp_route_lookup"
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
int fib_multipath_hash(const struct fib_info * fi, const struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587298016,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1793",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298016,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
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
int fib_multipath_hash(const struct fib_info * fi, const struct flowi4 * fl4, const struct sk_buff * skb)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587819536,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1806",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819536,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 705
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588169600,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1826",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588169600,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 695
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588353712,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1823",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588353712,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588756752,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1914",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588756752,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588980528,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980528,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589939824,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1917",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589939824,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589980784,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1923",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589980784,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 893
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589894608,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1911",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589894608,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 891
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590659424,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2022",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590659424,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1651
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592284640,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2044",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592284640,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1784
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594120976,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2039",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594120976,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1784
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594507920,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2037",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594507920,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1779
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595311072,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:2039",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595311072,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1779
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502586120,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502586120,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 844
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235291084,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235291084,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296173840,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296173840,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1140
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278740678,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278740678,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586912,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586912,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588298896,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588298896,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589023088,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589023088,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int fib_multipath_hash(const struct net * net, const struct flowi4 * fl4, const struct sk_buff * skb, struct flow_keys * flkeys)
```

```json
{
  "name": "fib_multipath_hash",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589061808,
      "name": "fib_multipath_hash",
      "external": true,
      "loc": "net/ipv4/route.c:1918",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/route.c:ip_route_input_slow",
        "net/ipv4/fib_semantics.c:fib_select_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589061808,
      "name": "fib_multipath_hash",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 901
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
int fib_multipath_hash(const struct fib_info * fi, const struct flowi4 * fl4, const struct sk_buff * skb)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct net * net</code>
</li>
<li>
<b>Param added. </b>
<code>struct flow_keys * flkeys</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct fib_info * fi</code>
</li>
</ul>
</details>
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
