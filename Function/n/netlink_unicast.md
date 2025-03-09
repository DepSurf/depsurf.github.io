# Function: <code>netlink_unicast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586505904,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1843",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:kauditd_send_skb",
        "kernel/audit.c:audit_send_list",
        "kernel/taskstats.c:send_reply",
        "kernel/taskstats.c:taskstats_exit",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586505904,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586948688,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1223",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_skb",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586948688,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587143664,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1240",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_unicast_skb",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143664,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587273920,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1274",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587273920,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587793952,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1287",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587793952,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588136560,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1326",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588136560,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 601
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588319312,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1319",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588319312,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588717472,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1311",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717472,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588941328,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588941328,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589832224,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/taskstats.c:send_cpu_listeners",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589832224,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 803
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589868688,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1313",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "kernel/taskstats.c:send_cpu_listeners",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589868688,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589774688,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1323",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589774688,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590534064,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1328",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_doit",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590534064,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592142688,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1328",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_doit",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592142688,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593967008,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_selftests_run",
        "net/core/devlink.c:devlink_nl_cmd_selftests_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_linecard_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_rate_get_doit",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593967008,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594343936,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1348",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/netdev-genl.c:netdev_nl_dev_get_doit",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_policer_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_new",
        "net/devlink/leftover.c:devlink_nl_cmd_region_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_param_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get",
        "net/devlink/leftover.c:devlink_dpipe_send_and_alloc_skb",
        "net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_sb_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_linecard_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_port_new_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_port_get_doit",
        "net/devlink/leftover.c:devlink_nl_cmd_rate_get_doit",
        "net/devlink/dev.c:devlink_nl_cmd_selftests_run",
        "net/devlink/dev.c:devlink_nl_cmd_selftests_get_doit",
        "net/devlink/dev.c:devlink_nl_cmd_info_get_doit",
        "net/devlink/dev.c:devlink_nl_cmd_eswitch_get_doit",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_nl_cmd_get_doit",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594343936,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 900
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595143696,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1350",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list_thread",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:taskstats_user_cmd",
        "kernel/taskstats.c:cmd_attr_pid",
        "kernel/taskstats.c:cgroupstats_user_cmd",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/netdev-genl.c:netdev_nl_queue_get_doit",
        "net/core/netdev-genl.c:netdev_nl_napi_get_doit",
        "net/core/netdev-genl.c:netdev_nl_dev_get_doit",
        "net/core/page_pool_user.c:netdev_nl_page_pool_get_do",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ethtool/netlink.c:ethnl_default_doit",
        "net/ethtool/features.c:features_send_reply",
        "net/ethtool/tunnels.c:ethnl_tunnel_info_doit",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/devlink/netlink.c:devlink_nl_msg_reply_and_new",
        "net/devlink/dev.c:devlink_nl_selftests_run_doit",
        "net/devlink/dev.c:devlink_nl_selftests_get_doit",
        "net/devlink/dev.c:devlink_nl_info_get_doit",
        "net/devlink/dev.c:devlink_nl_eswitch_get_doit",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_nl_get_doit",
        "net/devlink/port.c:devlink_nl_port_new_doit",
        "net/devlink/port.c:devlink_nl_port_get_doit",
        "net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_doit",
        "net/devlink/sb.c:devlink_nl_sb_port_pool_get_doit",
        "net/devlink/sb.c:devlink_nl_sb_pool_get_doit",
        "net/devlink/sb.c:devlink_nl_sb_get_doit",
        "net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit",
        "net/devlink/dpipe.c:devlink_dpipe_send_and_alloc_skb",
        "net/devlink/param.c:devlink_nl_param_get_doit",
        "net/devlink/region.c:devlink_nl_region_new_doit",
        "net/devlink/region.c:devlink_nl_region_get_doit",
        "net/devlink/health.c:devlink_nl_health_reporter_get_doit",
        "net/devlink/trap.c:devlink_nl_trap_policer_get_doit",
        "net/devlink/trap.c:devlink_nl_trap_group_get_doit",
        "net/devlink/trap.c:devlink_nl_trap_get_doit",
        "net/devlink/rate.c:devlink_nl_rate_get_doit",
        "net/devlink/linecard.c:devlink_nl_linecard_get_doit",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit",
        "net/handshake/tlshd.c:tls_handshake_accept"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595143696,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 906
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502539544,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502539544,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235247740,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235247740,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 532
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296114032,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296114032,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 708
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278704516,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278704516,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 466
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588547712,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588547712,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259696,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259696,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588879888,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netfilter/nfnetlink.c:nfnetlink_unicast",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_expect",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_stat_ct",
        "net/netfilter/nf_conntrack_netlink.c:ctnetlink_get_conntrack",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588879888,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
int netlink_unicast(struct sock * ssk, struct sk_buff * skb, u32 portid, int nonblock)
```

```json
{
  "name": "netlink_unicast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021952,
      "name": "netlink_unicast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1312",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:audit_receive_msg",
        "kernel/audit.c:audit_send_reply_thread",
        "kernel/audit.c:audit_send_list",
        "kernel/audit.c:kauditd_send_queue",
        "kernel/taskstats.c:taskstats_exit",
        "kernel/taskstats.c:send_reply",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnl_stats_get",
        "net/core/rtnetlink.c:rtnl_fdb_get",
        "net/core/rtnetlink.c:rtnl_getlink",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_trap_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_info_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_param_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_dpipe_send_and_alloc_skb",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_pool_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_sb_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_port_get_doit",
        "net/core/devlink.c:devlink_nl_cmd_get_doit",
        "net/sched/cls_api.c:tc_chain_notify",
        "net/sched/cls_api.c:tfilter_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_ack",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/fib_frontend.c:nl_fib_input",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_err",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021952,
      "name": "netlink_unicast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 536
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
