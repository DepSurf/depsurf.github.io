# Function: <code>rt6_uncached_list_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587061211,
      "name": "rt6_uncached_list_add",
      "external": false,
      "loc": "net/ipv6/route.c:118",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587513138,
      "name": "rt6_uncached_list_add",
      "external": false,
      "loc": "net/ipv6/route.c:119",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pol_route"
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
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587717282,
      "name": "rt6_uncached_list_add",
      "external": false,
      "loc": "net/ipv6/route.c:121",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_pol_route"
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587853536,
      "name": "rt6_uncached_list_add",
      "external": false,
      "loc": "net/ipv6/route.c:127",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587853536,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588382720,
      "name": "rt6_uncached_list_add",
      "external": false,
      "loc": "net/ipv6/route.c:131",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382720,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588762816,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:135",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588762816,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588983040,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:135",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588983040,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589431952,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:132",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589431952,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589656304,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656304,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590677593,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590669872,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590738030,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:134",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590730288,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590663242,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:137",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590655568,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591478666,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:137",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591469488,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593161886,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:138",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593152048,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595059918,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:138",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595049712,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595453185,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:138",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595443168,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596295291,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:138",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596285168,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503342432,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503342432,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236008368,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236008368,
      "name": "rt6_uncached_list_add",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297105472,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297105472,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279351602,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279351602,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589260672,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589260672,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588985664,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985664,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589697536,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589697536,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_add",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589747264,
      "name": "rt6_uncached_list_add",
      "external": true,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/xfrm6_policy.c:xfrm6_fill_dst"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589747264,
      "name": "rt6_uncached_list_add",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void rt6_uncached_list_add(struct rt6_info * rt)
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
