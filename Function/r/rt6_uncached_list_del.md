# Function: <code>rt6_uncached_list_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587058367,
      "name": "rt6_uncached_list_del",
      "external": false,
      "loc": "net/ipv6/route.c:130",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
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
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587509295,
      "name": "rt6_uncached_list_del",
      "external": false,
      "loc": "net/ipv6/route.c:131",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
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
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587713439,
      "name": "rt6_uncached_list_del",
      "external": false,
      "loc": "net/ipv6/route.c:133",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
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
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587862847,
      "name": "rt6_uncached_list_del",
      "external": false,
      "loc": "net/ipv6/route.c:138",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
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
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588400545,
      "name": "rt6_uncached_list_del",
      "external": false,
      "loc": "net/ipv6/route.c:142",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588756679,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:146",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588748032,
      "name": "rt6_uncached_list_del.part.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588762928,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588976858,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:146",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966992,
      "name": "rt6_uncached_list_del.part.80",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071588983152,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589420602,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:143",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589410944,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589432064,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589644922,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635184,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589656416,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590653833,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590645328,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071590669984,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590716713,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:145",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590705424,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071590730400,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590641353,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:148",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590630976,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071590655680,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591453881,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:148",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591444096,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071591469600,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593135857,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:149",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593152160,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595033073,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:149",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595049840,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595426577,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:149",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595443296,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596267681,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:149",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596285296,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503326304,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503326000,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
    },
    {
      "addr": 18446603336503342632,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235995252,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235986792,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    },
    {
      "addr": 3236008460,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297088340,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297077616,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 13835058055297105616,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279335702,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279335544,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    },
    {
      "addr": 18446743936279351714,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589249290,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589239552,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589260784,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588974282,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964544,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071588985776,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589686154,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676416,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589697648,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```

```json
{
  "name": "rt6_uncached_list_del",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589735482,
      "name": "rt6_uncached_list_del",
      "external": true,
      "loc": "net/ipv6/route.c:144",
      "file": "net/ipv6/route.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/route.c:ip6_dst_destroy"
      ],
      "caller_func": [
        "net/ipv6/route.c:ip6_dst_destroy",
        "net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589725552,
      "name": "rt6_uncached_list_del.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    },
    {
      "addr": 18446744071589747376,
      "name": "rt6_uncached_list_del",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void rt6_uncached_list_del(struct rt6_info * rt)
```
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
