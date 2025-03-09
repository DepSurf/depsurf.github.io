# Function: <code>replace_nexthop_grp</code>

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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589158303,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:837",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589382415,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590368088,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:935",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590425396,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1074",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:replace_nexthop"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590348096,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1913",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590348096,
      "name": "replace_nexthop_grp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1934",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591137792,
      "name": "replace_nexthop_grp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1016
    },
    {
      "addr": 18446744071592732096,
      "name": "replace_nexthop_grp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1932",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592792528,
      "name": "replace_nexthop_grp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071594618621,
      "name": "replace_nexthop_grp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1932",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594666688,
      "name": "replace_nexthop_grp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071596353427,
      "name": "replace_nexthop_grp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1932",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595059040,
      "name": "replace_nexthop_grp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
    },
    {
      "addr": 18446744071596882251,
      "name": "replace_nexthop_grp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1955",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595872048,
      "name": "replace_nexthop_grp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1052
    },
    {
      "addr": 18446744071597806423,
      "name": "replace_nexthop_grp.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503025544,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235714980,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296723348,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279095872,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588988591,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588700527,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589424975,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
  "name": "replace_nexthop_grp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589468543,
      "name": "replace_nexthop_grp",
      "external": false,
      "loc": "net/ipv4/nexthop.c:839",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int replace_nexthop_grp(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```
</details>
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
