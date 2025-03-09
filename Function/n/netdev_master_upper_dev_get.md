# Function: <code>netdev_master_upper_dev_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586268432,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:4961",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/netpoll.c:netpoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586268432,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586694016,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:5305",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/netpoll.c:netpoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586694016,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586880240,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:5480",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/netpoll.c:netpoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586880240,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587005264,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:5686",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/rtnetlink.c:if_nlmsg_size",
        "net/core/netpoll.c:netpoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587005264,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587503856,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:5827",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587503856,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587807856,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:5957",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587807856,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587943376,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6532",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587943376,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588252880,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6542",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252880,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588458096,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588458096,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325568,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6876",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:pneigh_dump_table",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_slave_info_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325568,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589324688,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:7033",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:pneigh_dump_table",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_slave_info_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589324688,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589220352,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:7292",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:nh_dump_filtered",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589220352,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:7282",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:nh_dump_filtered",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592695841,
      "name": "netdev_master_upper_dev_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071589949168,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6803",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:nh_dump_filtered",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_del",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594581518,
      "name": "netdev_master_upper_dev_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071591484752,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6789",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:nh_dump_filtered",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_del",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596323216,
      "name": "netdev_master_upper_dev_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071593253856,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6794",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:nh_dump_filtered",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_del",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596853305,
      "name": "netdev_master_upper_dev_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071593714736,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6912",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_table",
        "net/core/rtnetlink.c:if_nlmsg_stats_size",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:do_set_master",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_link_fill",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:nh_dump_filtered",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_del",
        "net/switchdev/switchdev.c:__switchdev_handle_port_obj_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597778296,
      "name": "netdev_master_upper_dev_get.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071594494288,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501983152,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501983152,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234737300,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234737300,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295413568,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295413568,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278281436,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278281436,
      "name": "netdev_master_upper_dev_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588064880,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588064880,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587777968,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587777968,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588396656,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396656,
      "name": "netdev_master_upper_dev_get",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct net_device * netdev_master_upper_dev_get(struct net_device * dev)
```

```json
{
  "name": "netdev_master_upper_dev_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588533072,
      "name": "netdev_master_upper_dev_get",
      "external": true,
      "loc": "net/core/dev.c:6485",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/neighbour.c:neigh_dump_info",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_bridge_dellink",
        "net/core/rtnetlink.c:rtnl_bridge_setlink",
        "net/core/rtnetlink.c:rtnl_bridge_getlink",
        "net/core/rtnetlink.c:ndo_dflt_bridge_getlink",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_dump",
        "net/core/rtnetlink.c:rtnl_fdb_del",
        "net/core/rtnetlink.c:rtnl_fdb_add",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/core/netpoll.c:netpoll_setup",
        "net/ipv4/nexthop.c:rtm_dump_nexthop",
        "net/l3mdev/l3mdev.c:l3mdev_master_upper_ifindex_by_index_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588533072,
      "name": "netdev_master_upper_dev_get",
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
