# Function: <code>mld_in_v1_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587139888,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1150",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587139888,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587592576,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1150",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587592576,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587796848,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1164",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587796848,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587954160,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1164",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587954160,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588490000,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1164",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588490000,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588853184,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1189",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588853184,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589076704,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1189",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076704,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589530864,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589530864,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589754944,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589754944,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590782414,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1185",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_rejoin_groups",
        "net/ipv6/mcast.c:ipv6_mc_rejoin_groups",
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590843198,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1185",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_rejoin_groups",
        "net/ipv6/mcast.c:ipv6_mc_rejoin_groups",
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590769369,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1221",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added"
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
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591586441,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1226",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added",
        "net/ipv6/mcast.c:igmp6_group_added"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593292820,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1226",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593267008,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595196644,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1226",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595169392,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595592404,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1226",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595564944,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596435268,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1226",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv6/mcast.c:ipv6_mc_init_dev",
        "net/ipv6/mcast.c:ipv6_mc_up"
      ],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:mld_mca_work",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596407744,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503449968,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503449968,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236109912,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236109912,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297236528,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297236528,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279437254,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279437254,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589359312,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589359312,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589084304,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589084304,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589796176,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589796176,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```

```json
{
  "name": "mld_in_v1_mode",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589846896,
      "name": "mld_in_v1_mode",
      "external": false,
      "loc": "net/ipv6/mcast.c:1188",
      "file": "net/ipv6/mcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/ipv6/mcast.c:ipv6_mc_netdev_event",
        "net/ipv6/mcast.c:ipv6_mc_reset",
        "net/ipv6/mcast.c:igmp6_timer_handler",
        "net/ipv6/mcast.c:mld_ifc_timer_expire",
        "net/ipv6/mcast.c:ip6_mc_del1_src",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:mld_dad_timer_expire",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/ipv6/mcast.c:igmp6_group_added"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589846896,
      "name": "mld_in_v1_mode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
bool mld_in_v1_mode(const struct inet6_dev * idev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool mld_in_v1_mode(const struct inet6_dev * idev)
```
</details>
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
