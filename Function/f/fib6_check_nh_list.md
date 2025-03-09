# Function: <code>fib6_check_nh_list</code>

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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589149360,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:597",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149360,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589373472,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589373472,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590365056,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:673",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590365056,
      "name": "fib6_check_nh_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590420048,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:801",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590420048,
      "name": "fib6_check_nh_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590332384,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1310",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590332384,
      "name": "fib6_check_nh_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591120896,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1310",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591120896,
      "name": "fib6_check_nh_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592774352,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1311",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592774352,
      "name": "fib6_check_nh_list",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594647712,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1311",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594647712,
      "name": "fib6_check_nh_list",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595040144,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1311",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595040144,
      "name": "fib6_check_nh_list",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595852960,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:1334",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595852960,
      "name": "fib6_check_nh_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503016368,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503016368,
      "name": "fib6_check_nh_list.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```

```json
{
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235707176,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235707176,
      "name": "fib6_check_nh_list",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296711008,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296711008,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279088526,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279088526,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588979648,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588979648,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588691584,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691584,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589416032,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589416032,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
  "name": "fib6_check_nh_list",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589459568,
      "name": "fib6_check_nh_list",
      "external": false,
      "loc": "net/ipv4/nexthop.c:599",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:rtm_new_nexthop",
        "net/ipv4/nexthop.c:rtm_new_nexthop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589459568,
      "name": "fib6_check_nh_list.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
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
int fib6_check_nh_list(struct nexthop * old, struct nexthop * new, struct netlink_ext_ack * extack)
```
</details>
</li>
</ul>
