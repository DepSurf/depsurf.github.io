# Function: <code>call_fib6_entry_notifiers</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct rt6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588419376,
      "name": "call_fib6_entry_notifiers",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:354",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588419376,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588790960,
      "name": "call_fib6_entry_notifiers",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:402",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589011344,
      "name": "call_fib6_entry_notifiers",
      "external": false,
      "loc": "net/ipv6/ip6_fib.c:401",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add",
        "net/ipv6/ip6_fib.c:fib6_add"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458528,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458528,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589682912,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589682912,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590698799,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:388",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590700864,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590759360,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:389",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590761408,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590686166,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:389",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590688208,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591502102,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:390",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591504144,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593186961,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:391",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593188912,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595086081,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:390",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595088144,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595479822,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:390",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595481888,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596323918,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:390",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596321744,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503372224,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503372224,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236036096,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236036096,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297142064,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297142064,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279375188,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279375188,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287280,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287280,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589012272,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012272,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589724144,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724144,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774512,
      "name": "call_fib6_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:371",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:fib6_rt_update",
        "net/ipv6/ip6_fib.c:fib6_del",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node",
        "net/ipv6/ip6_fib.c:fib6_add_rt2node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774512,
      "name": "call_fib6_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct rt6_info * rt, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct rt6_info * rt, struct netlink_ext_ack * extack)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int call_fib6_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, struct netlink_ext_ack * extack)
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
