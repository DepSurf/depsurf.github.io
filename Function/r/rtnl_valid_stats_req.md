# Function: <code>rtnl_valid_stats_req</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588378048,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:4977",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588378048,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588584448,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588584448,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589429824,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5215",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589429824,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589430032,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5307",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589430032,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589328736,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5309",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589328736,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590058544,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5330",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058544,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603504,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5730",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603504,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593384912,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5781",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593384912,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593847184,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5874",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593847184,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594629200,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5904",
      "file": "net/core/rtnetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_set",
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594629200,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502130472,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502130472,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234874072,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234874072,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295593104,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295593104,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278392406,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278392406,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588191184,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191184,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587904016,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587904016,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588523008,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588523008,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
```

```json
{
  "name": "rtnl_valid_stats_req",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588660288,
      "name": "rtnl_valid_stats_req",
      "external": false,
      "loc": "net/core/rtnetlink.c:5008",
      "file": "net/core/rtnetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_stats_dump",
        "net/core/rtnetlink.c:rtnl_stats_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660288,
      "name": "rtnl_valid_stats_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
int rtnl_valid_stats_req(const struct nlmsghdr * nlh, bool strict_check, bool is_dump, struct netlink_ext_ack * extack)
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
