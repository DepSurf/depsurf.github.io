# Function: <code>netlink_broadcast</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586495648,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:2127",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/af_netlink.c:nlmsg_notify"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586495648,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586950730,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1434",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:audit_log_end",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942080,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587145706,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1451",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_thread",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587137328,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587276618,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1486",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587268336,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587796610,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1499",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587788144,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588139297,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1538",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588129856,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588321995,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1531",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312352,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588720073,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1531",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588710352,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588943977,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588934256,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589835276,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "lib/kobject_uevent.c:uevent_net_broadcast",
        "lib/kobject_uevent.c:uevent_net_broadcast_tagged",
        "lib/kobject_uevent.c:uevent_net_broadcast_untagged",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_mcast",
        "net/netlink/genetlink.c:genlmsg_mcast",
        "net/ethtool/netlink.c:ethnl_multicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589826896,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589871756,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1533",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "lib/kobject_uevent.c:uevent_net_broadcast",
        "lib/kobject_uevent.c:uevent_net_broadcast_tagged",
        "lib/kobject_uevent.c:uevent_net_broadcast_untagged",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_report",
        "net/core/drop_monitor.c:net_dm_packet_report",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_mcast",
        "net/netlink/genetlink.c:genlmsg_mcast",
        "net/ethtool/netlink.c:ethnl_multicast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861760,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589777872,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1543",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ethtool/netlink.c:ethnl_multicast",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589767808,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590537281,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1548",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_policer_notify",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_rate_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ethtool/netlink.c:ethnl_multicast",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590527104,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592138448,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1490",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:devlink_linecard_notify",
        "net/core/devlink.c:devlink_rate_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ethtool/netlink.c:ethnl_multicast",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592138448,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593962640,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1510",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_linecard_notify",
        "net/core/devlink.c:devlink_rate_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ethtool/netlink.c:ethnl_multicast",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593962640,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594340608,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1510",
      "file": "net/netlink/af_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_netlink.c:thermal_genl_send_event",
        "drivers/thermal/thermal_netlink.c:thermal_genl_sampling_temp",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/ethtool/netlink.c:ethnl_multicast",
        "net/devlink/leftover.c:devlink_nl_region_notify",
        "net/devlink/leftover.c:devlink_linecard_notify",
        "net/devlink/leftover.c:devlink_rate_notify",
        "net/devlink/leftover.c:devlink_port_notify",
        "net/devlink/dev.c:devlink_notify",
        "net/mptcp/pm_netlink.c:mptcp_event",
        "net/mptcp/pm_netlink.c:mptcp_event_pm_listener",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_announced",
        "net/mptcp/pm_netlink.c:mptcp_event_addr_removed",
        "net/handshake/netlink.c:handshake_genl_notify",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594340608,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595145457,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1571",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "security/selinux/netlink.c:selnl_notify",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast",
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595140512,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502541984,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502527376,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235250380,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235238620,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296117484,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296102368,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278706614,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278698230,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588550361,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588540640,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588262345,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/scsi/scsi_transport_fc.c:fc_host_post_fc_event",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588252640,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588882537,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588872816,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
int netlink_broadcast(struct sock * ssk, struct sk_buff * skb, u32 portid, u32 group, gfp_t allocation)
```

```json
{
  "name": "netlink_broadcast",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589024601,
      "name": "netlink_broadcast",
      "external": true,
      "loc": "net/netlink/af_netlink.c:1532",
      "file": "net/netlink/af_netlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/af_netlink.c:nlmsg_notify",
        "net/netlink/af_netlink.c:netlink_sendmsg"
      ],
      "caller_func": [
        "kernel/audit.c:kauditd_send_multicast_skb",
        "fs/quota/netlink.c:quota_send_warning",
        "security/selinux/netlink.c:selnl_notify",
        "drivers/acpi/event.c:acpi_bus_generate_netlink_event",
        "drivers/connector/connector.c:cn_netlink_send_mult",
        "drivers/thermal/thermal_core.c:thermal_generate_netlink_event",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/rtnetlink.c:rtnetlink_send",
        "net/core/sock_diag.c:sock_diag_broadcast_destroy_work",
        "net/core/drop_monitor.c:net_dm_hw_packet_work",
        "net/core/drop_monitor.c:net_dm_packet_work",
        "net/core/drop_monitor.c:net_dm_hw_summary_work",
        "net/core/drop_monitor.c:send_dm_alert",
        "net/core/devlink.c:devlink_trap_notify",
        "net/core/devlink.c:devlink_trap_group_notify",
        "net/core/devlink.c:devlink_nl_region_notify",
        "net/core/devlink.c:devlink_param_notify",
        "net/core/devlink.c:__devlink_flash_update_notify",
        "net/core/devlink.c:devlink_port_notify",
        "net/core/devlink.c:devlink_notify",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genlmsg_multicast_allns",
        "net/netlink/genetlink.c:genl_ctrl_event",
        "lib/kobject_uevent.c:uevent_net_rcv_skb",
        "lib/kobject_uevent.c:kobject_uevent_env",
        "lib/kobject_uevent.c:kobject_uevent_env"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014336,
      "name": "netlink_broadcast",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
