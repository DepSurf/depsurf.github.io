# Function: <code>ip6_hold_safe</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt, bool null_fallback)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588400768,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:901",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:rt6_get_dflt_router",
        "net/ipv6/route.c:rt6_get_route_info",
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400768,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt, bool null_fallback)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588754368,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1017",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588754368,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt, bool null_fallback)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588974608,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1018",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588974608,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589417092,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1163",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589417056,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071589450394,
      "name": "ip6_hold_safe.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589641296,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589641296,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590650512,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1170",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590650512,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590710704,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1153",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590710704,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590636736,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1156",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590636736,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591450512,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1156",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591450512,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593131408,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1159",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593131408,
      "name": "ip6_hold_safe",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595028336,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1159",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595028336,
      "name": "ip6_hold_safe",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595420064,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1158",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595420064,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596261888,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1160",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596261888,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503324336,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503324336,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235994728,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235994728,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297090976,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297090976,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279342286,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279342286,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589245664,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245664,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588970656,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588970656,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589682528,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682528,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt)
```

```json
{
  "name": "ip6_hold_safe",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589731680,
      "name": "ip6_hold_safe",
      "external": false,
      "loc": "net/ipv6/route.c:1169",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:__ip6_route_redirect",
        "net/ipv6/route.c:ip6_pol_route",
        "net/ipv6/route.c:ip6_pol_route_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589731680,
      "name": "ip6_hold_safe",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
bool ip6_hold_safe(struct net * net, struct rt6_info * * prt, bool null_fallback)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool null_fallback</code>
</li>
</ul>
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
