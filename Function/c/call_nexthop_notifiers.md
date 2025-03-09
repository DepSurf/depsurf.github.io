# Function: <code>call_nexthop_notifiers</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590359157,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:39",
      "file": "net/ipv4/nexthop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/nexthop.c:__remove_nexthop_fib"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590421024,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:131",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590421024,
      "name": "call_nexthop_notifiers",
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
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590337872,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:222",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590337872,
      "name": "call_nexthop_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 621
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
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:222",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591134352,
      "name": "call_nexthop_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    },
    {
      "addr": 18446744071592731751,
      "name": "call_nexthop_notifiers.cold",
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
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:223",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592788736,
      "name": "call_nexthop_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071594618183,
      "name": "call_nexthop_notifiers.cold",
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
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:223",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594662656,
      "name": "call_nexthop_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
    },
    {
      "addr": 18446744071596352976,
      "name": "call_nexthop_notifiers.cold",
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
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:223",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595054992,
      "name": "call_nexthop_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071596881800,
      "name": "call_nexthop_notifiers.cold",
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
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```

```json
{
  "name": "call_nexthop_notifiers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "call_nexthop_notifiers",
      "external": false,
      "loc": "net/ipv4/nexthop.c:223",
      "file": "net/ipv4/nexthop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/nexthop.c:nexthop_net_exit_batch",
        "net/ipv4/nexthop.c:insert_nexthop",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single",
        "net/ipv4/nexthop.c:replace_nexthop_single_notify",
        "net/ipv4/nexthop.c:replace_nexthop_grp",
        "net/ipv4/nexthop.c:remove_nh_grp_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595868000,
      "name": "call_nexthop_notifiers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    },
    {
      "addr": 18446744071597805972,
      "name": "call_nexthop_notifiers.cold",
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int call_nexthop_notifiers(struct net * net, enum nexthop_event_type event_type, struct nexthop * nh, struct netlink_ext_ack * extack)
```
</details>
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
