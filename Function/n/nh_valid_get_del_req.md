# Function: <code>nh_valid_get_del_req</code>

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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589153168,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1484",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589153168,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589377280,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589377280,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590362928,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1622",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590362928,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590418368,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1845",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590418368,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590342862,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2942",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591127662,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2971",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592781461,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2971",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594655045,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2971",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595047445,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2971",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595860485,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2994",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503020192,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503020192,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235710200,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235710200,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296715872,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296715872,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279092768,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279092768,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588983456,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588983456,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588695392,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588695392,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589419840,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589419840,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nh_valid_get_del_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589463424,
      "name": "nh_valid_get_del_req",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1486",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_get_nexthop",
        "net/ipv4/nexthop.c:rtm_del_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589463424,
      "name": "nh_valid_get_del_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int nh_valid_get_del_req(struct nlmsghdr * nlh, u32 * id, struct netlink_ext_ack * extack)
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
