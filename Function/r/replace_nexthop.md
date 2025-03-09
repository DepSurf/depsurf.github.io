# Function: <code>replace_nexthop</code>

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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589157838,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:932",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589381950,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590367760,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1030",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590367760,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590425072,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1243",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590425072,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 740
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590350336,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2198",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590350336,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2221",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591139424,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 845
    },
    {
      "addr": 18446744071592732610,
      "name": "replace_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2220",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592794176,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071594619139,
      "name": "replace_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2220",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594668384,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071596353945,
      "name": "replace_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2220",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595060800,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071596882769,
      "name": "replace_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, const struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2243",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:insert_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595873808,
      "name": "replace_nexthop",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 836
    },
    {
      "addr": 18446744071597806941,
      "name": "replace_nexthop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503024996,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235714568,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296722600,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279095478,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588988126,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588700062,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589424510,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
  "name": "replace_nexthop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589468078,
      "name": "replace_nexthop",
      "external": false,
      "loc": "net/ipv4/nexthop.c:934",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int replace_nexthop(struct net * net, struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nh_config * cfg</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, old, new, extack</code> ➡️ <code>net, old, new, cfg, extack</code>
</li>
</ul>
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
