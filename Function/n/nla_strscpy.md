# Function: <code>nla_strscpy</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119184,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:725",
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
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119184,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584999456,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:725",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584999456,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440672,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:725",
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
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/devinet.c:rtm_to_ifaddr",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440672,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586581264,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:725",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586581264,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587821984,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:740",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tc_ctl_chain",
        "net/sched/cls_api.c:tc_get_tfilter",
        "net/sched/cls_api.c:tc_del_tfilter",
        "net/sched/cls_api.c:tc_new_tfilter",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587821984,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588093408,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:740",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tcf_proto_check_kind",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588093408,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
```

```json
{
  "name": "nla_strscpy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429280,
      "name": "nla_strscpy",
      "external": true,
      "loc": "lib/nlattr.c:772",
      "file": "lib/nlattr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:parse",
        "drivers/net/netkit.c:netkit_new_link",
        "drivers/net/netkit.c:netkit_new_link",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:__rtnl_newlink",
        "net/core/rtnetlink.c:rtnl_newlink_create",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_dellink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:rtnl_setlink",
        "net/core/rtnetlink.c:do_setlink",
        "net/core/rtnetlink.c:rtnl_dump_ifinfo",
        "net/sched/sch_api.c:qdisc_create",
        "net/sched/cls_api.c:tcf_proto_check_kind",
        "net/sched/act_api.c:tc_action_load_ops",
        "net/ipv4/fib_semantics.c:fib_metrics_match",
        "net/ipv4/metrics.c:ip_metrics_convert",
        "net/devlink/netlink.c:devlink_nl_notify_filter_set_doit",
        "net/devlink/netlink.c:devlink_nl_notify_filter_set_doit",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429280,
      "name": "nla_strscpy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
ssize_t nla_strscpy(char * dst, const struct nlattr * nla, size_t dstsize)
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
