# Function: <code>genlmsg_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586509424,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:496",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586509424,
      "name": "genlmsg_put",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586951760,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:476",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951760,
      "name": "genlmsg_put",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587147200,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:438",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587147200,
      "name": "genlmsg_put",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587278112,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:438",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587278112,
      "name": "genlmsg_put",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587798128,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:439",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587798128,
      "name": "genlmsg_put",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140848,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:440",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140848,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588323568,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588323568,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721904,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721904,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588945568,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945568,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589836480,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:426",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589836480,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589877534,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:496",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep"
      ],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589873040,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589783518,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:496",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep"
      ],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589779072,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590542942,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:488",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep"
      ],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590538640,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592147856,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:488",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592147856,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593973936,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:733",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_policer_fill",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify_build",
        "net/core/devlink.c:devlink_nl_cmd_selftests_run",
        "net/core/devlink.c:devlink_nl_selftests_fill",
        "net/core/devlink.c:devlink_nl_flash_update_fill",
        "net/core/devlink.c:devlink_nl_cmd_reload",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593973936,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594351040,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:733",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/devlink/leftover.c:devlink_nl_trap_policer_fill",
        "net/devlink/leftover.c:devlink_nl_trap_group_fill",
        "net/devlink/leftover.c:devlink_nl_trap_fill",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_region_notify_build",
        "net/devlink/leftover.c:devlink_nl_port_fill",
        "net/devlink/dev.c:devlink_nl_cmd_selftests_run",
        "net/devlink/dev.c:devlink_nl_selftests_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_cmd_reload",
        "net/devlink/dev.c:devlink_nl_fill",
        "net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_limits",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_dump_addrs",
        "net/mptcp/pm_netlink.c:mptcp_nl_cmd_get_addr",
        "net/handshake/netlink.c:handshake_genl_put",
        "net/handshake/netlink.c:handshake_genl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594351040,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595149968,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:891",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/regulator/event.c:reg_generate_netlink_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_doit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_cmd_dumpit",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_device_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_device_id_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_nl_pin_id_get_doit",
        "drivers/dpll/dpll_netlink.c:dpll_pin_event_send",
        "drivers/dpll/dpll_netlink.c:dpll_device_event_send",
        "net/core/netdev-genl.c:netdev_nl_queue_fill_one",
        "net/core/netdev-genl.c:netdev_nl_napi_fill_one",
        "net/core/netdev-genl.c:netdev_nl_dev_fill",
        "net/core/page_pool_user.c:page_pool_nl_fill",
        "net/core/page_pool_user.c:page_pool_nl_stats_fill",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_packet_report_fill",
        "net/core/drop_monitor.c:net_dm_hw_summary_report_fill",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/netlink/genetlink.c:ctrl_dumppolicy_prep",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ethtool/netlink.c:ethnl_default_notify",
        "net/ethtool/netlink.c:ethnl_default_dumpit",
        "net/ethtool/netlink.c:ethnl_dump_put",
        "net/ethtool/netlink.c:ethnl_reply_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpsc",
        "net/ipv6/ioam6.c:ioam6_genl_dumpns",
        "net/devlink/dev.c:devlink_nl_selftests_run_doit",
        "net/devlink/dev.c:devlink_nl_selftests_fill",
        "net/devlink/dev.c:devlink_nl_flash_update_fill",
        "net/devlink/dev.c:devlink_nl_reload_doit",
        "net/devlink/dev.c:devlink_nl_fill",
        "net/devlink/port.c:devlink_nl_port_fill",
        "net/devlink/region.c:devlink_nl_region_read_dumpit",
        "net/devlink/region.c:devlink_nl_region_notify_build",
        "net/devlink/health.c:devlink_nl_health_reporter_dump_get_dumpit",
        "net/devlink/health.c:devlink_nl_health_reporter_fill",
        "net/devlink/trap.c:devlink_nl_trap_policer_fill",
        "net/devlink/trap.c:devlink_nl_trap_group_fill",
        "net/devlink/trap.c:devlink_nl_trap_fill",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_limits_doit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_dumpit",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_get_addr_doit",
        "net/handshake/netlink.c:handshake_genl_put",
        "net/handshake/netlink.c:handshake_genl_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595149968,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502545096,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502545096,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235252104,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_group_fill",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_protocols_cb",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_staticlist_gen",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235252104,
      "name": "genlmsg_put",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296120608,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296120608,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278708120,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278708120,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588551952,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588551952,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588263936,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588263936,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588884128,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588884128,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * genlmsg_put(struct sk_buff * skb, u32 portid, u32 seq, const struct genl_family * family, int flags, u8 cmd)
```

```json
{
  "name": "genlmsg_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589026192,
      "name": "genlmsg_put",
      "external": true,
      "loc": "net/netlink/genetlink.c:441",
      "file": "net/netlink/genetlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:prepare_reply",
        "kernel/taskstats.c:prepare_reply",
        "fs/quota/netlink.c:quota_send_warning",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/drop_monitor.c:net_dm_cmd_stats_get",
        "net/core/drop_monitor.c:net_dm_cmd_config_get",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:reset_per_cpu_data",
        "net/core/devlink.c:devlink_nl_trap_fill",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_nl_param_fill",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_nl_cmd_resource_dump",
        "net/core/devlink.c:devlink_nl_cmd_dpipe_table_get",
        "net/core/devlink.c:devlink_nl_cmd_eswitch_get_doit",
        "net/core/devlink.c:devlink_nl_port_fill",
        "net/core/devlink.c:devlink_nl_fill",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "net/netlink/genetlink.c:ctrl_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_cmd_get",
        "net/ipv4/tcp_metrics.c:tcp_metrics_nl_dump",
        "net/ipv6/seg6.c:seg6_genl_dumphmac",
        "net/ipv6/seg6.c:seg6_genl_get_tunsrc",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_version",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listdef",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_listall_cb",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_list",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_listall_cb",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_list",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_listall_cb",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_list",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_timeout",
        "net/ncsi/ncsi-netlink.c:ncsi_send_netlink_rsp",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl",
        "net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589026192,
      "name": "genlmsg_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct genl_family * family</code> ➡️ <code>const struct genl_family * family</code>
</li>
</ul>
</details>
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
