# Function: <code>remove_nexthop</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589155136,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:808",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155136,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589379232,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379232,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590366726,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:906",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590365968,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590423558,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1043",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590421920,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590347926,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1882",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590347008,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591138870,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1882",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591136896,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592793607,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1883",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592791504,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594667783,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1883",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594665600,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595060199,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1883",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595057968,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595873207,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1906",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch"
      ],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595870976,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503021536,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503021536,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235711616,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235711616,
      "name": "remove_nexthop",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296717664,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296717664,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279089858,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279089858,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588985408,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588985408,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588697344,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588697344,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589421792,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589421792,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
```

```json
{
  "name": "remove_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589465376,
      "name": "remove_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:810",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:rtm_del_nexthop",
        "net/ipv4/nexthop.c:nexthop_flush_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589465376,
      "name": "remove_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void remove_nexthop(struct net * net, struct nexthop * nh, struct nl_info * nlinfo)
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
