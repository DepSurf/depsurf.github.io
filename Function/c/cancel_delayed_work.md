# Function: <code>cancel_delayed_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470208,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2893",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_stop_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queue",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470208,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483968,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:2993",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_stop_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queue",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483968,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504720,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3032",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_stop_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queue",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504720,
      "name": "cancel_delayed_work",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493776,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3031",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "block/blk-core.c:blk_stop_queue",
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/thermal/thermal_core.c:handle_thermal_trip",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493776,
      "name": "cancel_delayed_work",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520480,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3045",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "block/blk-core.c:blk_stop_queue",
        "block/blk-mq.c:blk_mq_delay_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/thermal/thermal_core.c:handle_thermal_trip",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520480,
      "name": "cancel_delayed_work",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551104,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3119",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu",
        "block/blk-core.c:blk_stop_queue",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_core.c:release_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551104,
      "name": "cancel_delayed_work",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579587680,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3142",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579587680,
      "name": "cancel_delayed_work",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611776,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3242",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611776,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579636960,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636960,
      "name": "cancel_delayed_work",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674944,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3248",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674944,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654768,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3254",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/thermal/thermal_core.c:handle_thermal_trip",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654768,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661216,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3255",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661216,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738304,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3294",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738304,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834416,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3277",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/thermal/thermal_core.c:handle_thermal_trip",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834416,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579977968,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3284",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977968,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580027008,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3600",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027008,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062224,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3621",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/thermal/thermal_core.c:thermal_pm_notify",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_group_dropped",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062224,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490809176,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490809176,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224840140,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "sound/soc/soc-pcm.c:soc_pcm_prepare",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224840140,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283632144,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/vio.c:vio_cmo_balance",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq",
        "drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport",
        "drivers/scsi/scsi_transport_srp.c:srp_reconnect_rport",
        "drivers/scsi/scsi_transport_srp.c:store_reconnect_delay",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283632144,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271489950,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_completed",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_ifdown",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:addrconf_dad_stop",
        "net/ipv6/addrconf.c:ipv6_del_addr",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271489950,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613264,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613264,
      "name": "cancel_delayed_work",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542256,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_add",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_add",
        "drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete",
        "drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542256,
      "name": "cancel_delayed_work",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579610544,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579610544,
      "name": "cancel_delayed_work",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648624,
      "name": "cancel_delayed_work",
      "external": true,
      "loc": "kernel/workqueue.c:3251",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu",
        "block/blk-mq.c:blk_mq_stop_hw_queues",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_disable_request",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_core.c:cleanup_slots",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_disable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_sysfs_enable_slot",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/regulator/core.c:regulator_disable_work",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_flush",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/core/netpoll.c:rcu_cleanup_netpoll_info",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv6/addrconf.c:addrconf_cleanup",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:inet6_ifa_finish_destroy",
        "net/ipv6/addrconf.c:addrconf_del_dad_work",
        "net/strparser/strparser.c:__strp_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648624,
      "name": "cancel_delayed_work",
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
