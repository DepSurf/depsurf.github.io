# Function: <code>genl_register_family</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genl_register_family",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595166680,
      "name": "genl_register_family",
      "external": false,
      "loc": "include/net/genetlink.h:135",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595238721,
      "name": "genl_register_family",
      "external": false,
      "loc": "include/net/genetlink.h:135",
      "file": "drivers/acpi/event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595307464,
      "name": "genl_register_family",
      "external": false,
      "loc": "include/net/genetlink.h:135",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "genl_register_family",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595341101,
      "name": "genl_register_family",
      "external": false,
      "loc": "include/net/genetlink.h:135",
      "file": "fs/quota/netlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/quota/netlink.c:quota_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595418849,
      "name": "genl_register_family",
      "external": false,
      "loc": "include/net/genetlink.h:135",
      "file": "drivers/acpi/event.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595490700,
      "name": "genl_register_family",
      "external": false,
      "loc": "include/net/genetlink.h:135",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587151648,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:321",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587151648,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1561
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587282496,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:321",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587282496,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1598
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587802576,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/netlink.c:quota_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587802576,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1666
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588144128,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144128,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1576
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588326848,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588326848,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588727084,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588728571,
      "name": "genl_register_family.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071588726944,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1516
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588950608,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588950608,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1553
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589843552,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589843552,
      "name": "genl_register_family.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
    },
    {
      "addr": 18446744071589844032,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589881872,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:392",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589881872,
      "name": "genl_register_family.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 469
    },
    {
      "addr": 18446744071589882352,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589788192,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:392",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788192,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 675
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590547616,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:384",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590547616,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592157584,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:384",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592157584,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 996
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593984928,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:629",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593984928,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594362032,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:629",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "net/core/netdev-genl.c:netdev_genl_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/devlink/core.c:devlink_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init",
        "net/handshake/netlink.c:handshake_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594362032,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622265445,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:778",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:genl_init"
      ],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/regulator/event.c:reg_event_init",
        "drivers/thermal/thermal_netlink.c:thermal_netlink_init",
        "drivers/dpll/dpll_core.c:dpll_init",
        "net/core/netdev-genl.c:netdev_genl_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/netlink/genetlink.c:genl_init",
        "net/ethtool/netlink.c:ethnl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/ipv6/ioam6.c:ioam6_init",
        "net/devlink/core.c:devlink_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink",
        "net/mptcp/pm_netlink.c:mptcp_pm_nl_init",
        "net/handshake/netlink.c:handshake_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595162096,
      "name": "genl_register_family.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 645
    },
    {
      "addr": 18446744071595162768,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502550104,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502550104,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1572
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235257372,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235257372,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1624
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296127824,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296127824,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 928
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278712474,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278712474,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1322
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588556992,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588556992,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1553
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588268976,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588268976,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1553
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588889168,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588889168,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1553
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
int genl_register_family(struct genl_family * family)
```

```json
{
  "name": "genl_register_family",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589031248,
      "name": "genl_register_family",
      "external": true,
      "loc": "net/netlink/genetlink.c:322",
      "file": "net/netlink/genetlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/taskstats.c:taskstats_init",
        "fs/quota/netlink.c:quota_init",
        "drivers/acpi/event.c:acpi_event_init",
        "drivers/thermal/thermal_core.c:thermal_init",
        "net/core/drop_monitor.c:init_net_drop_monitor",
        "net/core/devlink.c:devlink_init",
        "net/netlink/genetlink.c:genl_init",
        "net/ipv4/tcp_metrics.c:tcp_metrics_init",
        "net/ipv6/seg6.c:seg6_init",
        "net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init",
        "net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init",
        "net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init",
        "net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init",
        "net/ncsi/ncsi-netlink.c:ncsi_init_netlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589031248,
      "name": "genl_register_family",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1568
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int genl_register_family(struct genl_family * family)
```
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
