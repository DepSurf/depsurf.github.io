# Function: <code>nexthop_create_group</code>

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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589154512,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1082",
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
      "addr": 18446744071589154512,
      "name": "nexthop_create_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589378608,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
      "addr": 18446744071589378608,
      "name": "nexthop_create_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590366880,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1180",
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
      "addr": 18446744071590366880,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 695
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590424160,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1401",
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
      "addr": 18446744071590424160,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590339072,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2385",
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
      "addr": 18446744071590339072,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1055
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2408",
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
      "addr": 18446744071591132336,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1085
    },
    {
      "addr": 18446744071592731535,
      "name": "nexthop_create_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2408",
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
      "addr": 18446744071592786528,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
    },
    {
      "addr": 18446744071594617965,
      "name": "nexthop_create_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2408",
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
      "addr": 18446744071594659952,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1172
    },
    {
      "addr": 18446744071596352633,
      "name": "nexthop_create_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2408",
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
      "addr": 18446744071595052336,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
    },
    {
      "addr": 18446744071596881457,
      "name": "nexthop_create_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:2431",
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
      "addr": 18446744071595865712,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1124
    },
    {
      "addr": 18446744071597805754,
      "name": "nexthop_create_group.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503023904,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```

```json
{
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235713284,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
      "addr": 3235713284,
      "name": "nexthop_create_group",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055296721236,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279094612,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588984784,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
      "addr": 18446744071588984784,
      "name": "nexthop_create_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588696720,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
      "addr": 18446744071588696720,
      "name": "nexthop_create_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589421168,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
      "addr": 18446744071589421168,
      "name": "nexthop_create_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
  "name": "nexthop_create_group",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589464752,
      "name": "nexthop_create_group",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1084",
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
      "addr": 18446744071589464752,
      "name": "nexthop_create_group.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 617
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
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
struct nexthop * nexthop_create_group(struct net * net, struct nh_config * cfg)
```
</details>
</li>
</ul>
