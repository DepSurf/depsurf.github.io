# Function: <code>nh_create_ipv6</code>

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
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589150304,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1175",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589150304,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589374416,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589374416,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590357920,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1293",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590357920,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590417040,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1516",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590417040,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590332064,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2521",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332064,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591120544,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2545",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591120544,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592773968,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2545",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592773968,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594647312,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2545",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594647312,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595039744,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2545",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595039744,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595852560,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2568",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595852560,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503017352,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503017352,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235705944,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235705944,
      "name": "nh_create_ipv6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296712208,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296712208,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279090664,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279090664,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588980592,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588980592,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588692528,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588692528,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589416976,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416976,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_create_ipv6",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589460528,
      "name": "nh_create_ipv6",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1177",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589460528,
      "name": "nh_create_ipv6.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int nh_create_ipv6(struct net * net, struct nexthop * nh, struct nh_info * nhi, struct nh_config * cfg, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
