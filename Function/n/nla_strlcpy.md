# Function: <code>nla_strlcpy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127792,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:247",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127792,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422016,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:247",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422016,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583547648,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:247",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_ctl_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583547648,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583585312,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:255",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583585312,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583831344,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:309",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/core/fib_rules.c:fib_nl_newrule",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_create_info",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv6/route.c:ip6_convert_metrics"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583831344,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031312,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:309",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031312,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584112496,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:484",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584112496,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584301440,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584301440,
      "name": "nla_strlcpy",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584436160,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584436160,
      "name": "nla_strlcpy",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584998688,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:668",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_chain_tmplt_add",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584998688,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496321368,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496321368,
      "name": "nla_strlcpy",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229655948,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:linkinfo_to_kind_ops",
        "net/core/fib_rules.c:fib_nl2rule",
        "net/core/fib_rules.c:fib_nl2rule",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229655948,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290638528,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290638528,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275373646,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275373646,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584404896,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584404896,
      "name": "nla_strlcpy",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584340096,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584340096,
      "name": "nla_strlcpy",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584387808,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584387808,
      "name": "nla_strlcpy",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strlcpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584493872,
      "name": "nla_strlcpy",
      "external": true,
      "loc": "lib/nlattr.c:516",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584493872,
      "name": "nla_strlcpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
size_t nla_strlcpy(char * dst, const struct nlattr * nla, size_t dstsize)
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
