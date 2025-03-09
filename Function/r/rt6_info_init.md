# Function: <code>rt6_info_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587051592,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:317",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:__ip6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route"
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
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587518596,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:318",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
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
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587722724,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:320",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587854048,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:341",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587854048,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383152,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:347",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:__ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383152,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588742816,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:341",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588742816,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588963024,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963024,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589406960,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:341",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589406960,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589631200,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589631200,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590676225,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590736609,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:326",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590661841,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:329",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591477265,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:329",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593123680,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:334",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593123680,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595016000,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:334",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595016000,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595409536,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:334",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595409536,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596251072,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:334",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:icmp6_dst_alloc",
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_rt_cache_alloc",
        "net/ipv6/route.c:ip6_create_rt_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596251072,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503314456,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503314456,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235981060,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235981060,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297070480,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297070480,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279357170,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589235568,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589235568,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588960560,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588960560,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589672432,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672432,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
```

```json
{
  "name": "rt6_info_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589721408,
      "name": "rt6_info_init",
      "external": false,
      "loc": "net/ipv6/route.c:343",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_blackhole_route",
        "net/ipv6/route.c:ip6_dst_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721408,
      "name": "rt6_info_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
void rt6_info_init(struct rt6_info * rt)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void rt6_info_init(struct rt6_info * rt)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void rt6_info_init(struct rt6_info * rt)
```
</details>
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
void rt6_info_init(struct rt6_info * rt)
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
