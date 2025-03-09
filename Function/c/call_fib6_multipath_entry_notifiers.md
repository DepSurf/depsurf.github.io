# Function: <code>call_fib6_multipath_entry_notifiers</code>

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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589458640,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589458640,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589683024,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589683024,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590700960,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:402",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590700960,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590761504,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:403",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590761504,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590688320,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:403",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590688320,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591504256,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:404",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591504256,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593189024,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:405",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593189024,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595088272,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:404",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595088272,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595482016,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:404",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595482016,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596321872,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:404",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:__ip6_del_rt_siblings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596321872,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503372368,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503372368,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236036228,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236036228,
      "name": "call_fib6_multipath_entry_notifiers",
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297142208,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297142208,
      "name": "call_fib6_multipath_entry_notifiers",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279375282,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279375282,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287392,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287392,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589012384,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589012384,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589724256,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724256,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_fib6_multipath_entry_notifiers",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774624,
      "name": "call_fib6_multipath_entry_notifiers",
      "external": true,
      "loc": "net/ipv6/ip6_fib.c:385",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/route.c:ip6_route_multipath_add",
        "net/ipv6/route.c:ip6_route_del"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774624,
      "name": "call_fib6_multipath_entry_notifiers",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int call_fib6_multipath_entry_notifiers(struct net * net, enum fib_event_type event_type, struct fib6_info * rt, unsigned int nsiblings, struct netlink_ext_ack * extack)
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
