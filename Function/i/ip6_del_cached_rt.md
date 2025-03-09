# Function: <code>ip6_del_cached_rt</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588758491,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3250",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_del"
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
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588977884,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3230",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_route_del"
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589423360,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3809",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589423360,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589647680,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589647680,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590656673,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3875",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590656240,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590715794,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3859",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715360,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590640450,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3873",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590640032,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591453618,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:4003",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591453200,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593134850,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3979",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593134336,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595032018,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3979",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595031456,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595425506,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3977",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595424928,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596267378,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3979",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596266800,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503329336,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503329336,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236002752,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236002752,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297097600,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297097600,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279346850,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279346850,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589252048,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589252048,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588977040,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588977040,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688912,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688912,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
```

```json
{
  "name": "ip6_del_cached_rt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589738240,
      "name": "ip6_del_cached_rt",
      "external": false,
      "loc": "net/ipv6/route.c:3822",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_del",
        "net/ipv6/route.c:fib6_nh_del_cached_rt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589738240,
      "name": "ip6_del_cached_rt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
int ip6_del_cached_rt(struct fib6_config * cfg, struct fib6_info * rt, struct fib6_nh * nh)
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
