# Function: <code>nh_check_attr_group</code>

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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589151028,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:389",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589375140,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
int nh_check_attr_group(struct net * net, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590359536,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:440",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590359536,
      "name": "nh_check_attr_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 639
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
int nh_check_attr_group(struct net * net, struct nlattr * * tb, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590414512,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:568",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590414512,
      "name": "nh_check_attr_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590331024,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1042",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590331024,
      "name": "nh_check_attr_group.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 895
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1042",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591119360,
      "name": "nh_check_attr_group.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1047
    },
    {
      "addr": 18446744071592730130,
      "name": "nh_check_attr_group.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 401
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1043",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592772768,
      "name": "nh_check_attr_group.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
    },
    {
      "addr": 18446744071594616546,
      "name": "nh_check_attr_group.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1043",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594646080,
      "name": "nh_check_attr_group.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
    },
    {
      "addr": 18446744071596351383,
      "name": "nh_check_attr_group.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1043",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595038512,
      "name": "nh_check_attr_group.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1044
    },
    {
      "addr": 18446744071596880247,
      "name": "nh_check_attr_group.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1043",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595851408,
      "name": "nh_check_attr_group.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
    },
    {
      "addr": 18446744071597804326,
      "name": "nh_check_attr_group.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 513
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503018016,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235707924,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296713080,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279091224,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588981316,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588693252,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589417700,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
  "name": "nh_check_attr_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589461284,
      "name": "nh_check_attr_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:391",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_to_nh_config"
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
int nh_check_attr_group(struct net * net, struct nlattr * * tb, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int nh_check_attr_group(struct net * net, struct nlattr * * tb, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
