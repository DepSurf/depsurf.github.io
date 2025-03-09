# Function: <code>__remove_nexthop</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589155437,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:790",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155280,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
    },
    {
      "addr": 18446744071589158821,
      "name": "__remove_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589379376,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379376,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590365728,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:888",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:nexthop_add",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590365728,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590422688,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1025",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590422688,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 239
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590346512,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1864",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590346512,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591136586,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1864",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136368,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 525
    },
    {
      "addr": 18446744071592732033,
      "name": "__remove_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592791154,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1865",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592790928,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071594618552,
      "name": "__remove_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594665234,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1865",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594665008,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071596353358,
      "name": "__remove_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595057602,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1865",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595057376,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071596882182,
      "name": "__remove_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595870610,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1888",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595870384,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 568
    },
    {
      "addr": 18446744071597806354,
      "name": "__remove_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503021704,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503021704,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 932
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235711752,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235711752,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296717920,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296717920,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1368
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279089072,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279089072,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 786
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588985552,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985552,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588697488,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588697488,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589421936,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421936,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "__remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589465520,
      "name": "__remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:792",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:remove_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589465520,
      "name": "__remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
void __remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
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
