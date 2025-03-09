# Function: <code>valid_fdb_dump_strict</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588063744,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3836",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588063744,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588380608,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3903",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588380608,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588586976,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586976,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589438336,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4137",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589438336,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589438976,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4229",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589438976,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589338432,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4227",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589338432,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 435
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590068688,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4248",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590068688,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591612752,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4369",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591612752,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593394880,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4420",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593394880,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593859664,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4509",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593859664,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594642208,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:4542",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594642208,
      "name": "valid_fdb_dump_strict.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 497
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502134760,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502134760,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234885992,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295597152,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295597152,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278397124,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278397124,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588193712,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588193712,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587906544,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587906544,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588525536,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588525536,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```

```json
{
  "name": "valid_fdb_dump_strict",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588662880,
      "name": "valid_fdb_dump_strict",
      "external": false,
      "loc": "net/core/rtnetlink.c:3934",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_fdb_dump"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588662880,
      "name": "valid_fdb_dump_strict",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 366
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```
</details>
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
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int valid_fdb_dump_strict(const struct nlmsghdr * nlh, int * br_idx, int * brport_idx, struct netlink_ext_ack * extack)
```
</details>
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
