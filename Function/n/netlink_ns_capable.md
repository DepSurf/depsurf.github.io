# Function: <code>netlink_ns_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586488672,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1414",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_capable",
        "net/netlink/af_netlink.c:netlink_net_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586488672,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586934988,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:797",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586934912,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587130188,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:814",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130112,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587260748,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:848",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587260672,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587780124,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:850",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587780048,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588122549,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:885",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588122480,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588304805,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:880",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588304736,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588702677,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588702608,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588926549,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588926480,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589820028,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/devlink.c:devlink_netns_get",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589819840,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589856252,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:872",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/devlink.c:devlink_netns_get",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589856064,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589761868,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:882",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589761680,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590521084,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:885",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590520896,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592129034,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:885",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_rcv_msg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592128832,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593954538,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:898",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593954416,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594330970,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:898",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594330592,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595130666,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:901",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595130176,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502520652,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502520488,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235231116,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235231020,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296092832,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296092736,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278691446,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278691300,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588532933,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588532864,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588244933,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244864,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588865109,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865040,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
bool netlink_ns_capable(const struct sk_buff * skb, struct user_namespace * user_ns, int cap)
```

```json
{
  "name": "netlink_ns_capable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589006597,
      "name": "netlink_ns_capable",
      "external": true,
      "loc": "net/netlink/af_netlink.c:871",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_net_capable",
        "net/netlink/af_netlink.c:netlink_capable"
      ],
      "caller_func": [
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/sched/sch_api.c:tc_ctl_tclass",
        "net/sched/sch_api.c:tc_modify_qdisc",
        "net/sched/sch_api.c:tc_get_qdisc",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/netlink/genetlink.c:genl_family_rcv_msg",
        "lib/kobject_uevent.c:uevent_net_rcv_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589006528,
      "name": "netlink_ns_capable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
