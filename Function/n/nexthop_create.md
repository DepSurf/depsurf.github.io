# Function: <code>nexthop_create</code>

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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589157571,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1204",
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589381683,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590364288,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1323",
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
      "addr": 18446744071590364288,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590420224,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1546",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590420224,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590333456,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2551",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590333456,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2580",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591122048,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
    },
    {
      "addr": 18446744071592730844,
      "name": "nexthop_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2580",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592775648,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071594617274,
      "name": "nexthop_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2580",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594649088,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071596352111,
      "name": "nexthop_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2580",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595041472,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 397
    },
    {
      "addr": 18446744071596880927,
      "name": "nexthop_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2603",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595856864,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    },
    {
      "addr": 18446744071597804900,
      "name": "nexthop_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503024648,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```

```json
{
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235706244,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235706244,
      "name": "nexthop_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296721952,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279095266,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588987859,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588699795,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589424243,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
  "name": "nexthop_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589467811,
      "name": "nexthop_create",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1206",
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
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
struct nexthop * nexthop_create(struct net * net, struct nh_config * cfg, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
