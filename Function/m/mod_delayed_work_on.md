# Function: <code>mod_delayed_work_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470048,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1529",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_pidlist_stop",
        "kernel/cgroup.c:css_free_work_fn",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:wb_wakeup",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "block/blk-core.c:blk_run_queue_async",
        "block/genhd.c:disk_flush_events",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/power/charger-manager.c:_setup_polling",
        "drivers/power/charger-manager.c:cm_notify_event",
        "net/core/dst.c:__dst_free",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470048,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483808,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1585",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_pidlist_stop",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:blk_run_queue_async",
        "block/genhd.c:disk_flush_events",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/power/charger-manager.c:cm_notify_event",
        "drivers/power/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/dst.c:__dst_free",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483808,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504352,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1587",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_pidlist_stop",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:blk_run_queue_async",
        "block/genhd.c:disk_flush_events",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/power/supply/charger-manager.c:cm_notify_event",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "net/core/dst.c:__dst_free",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504352,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493456,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1586",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/blk-core.c:blk_run_queue_async",
        "block/genhd.c:disk_flush_events",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493456,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520160,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1587",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/blk-core.c:blk_run_queue_async",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_release",
        "drivers/watchdog/watchdog_dev.c:watchdog_ioctl",
        "drivers/watchdog/watchdog_dev.c:watchdog_start",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/watchdog/watchdog_dev.c:__watchdog_ping",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520160,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551632,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1585",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/blk-core.c:blk_run_queue_async",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551632,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588256,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1605",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588256,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612560,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1701",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:cec_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612560,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637760,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:cec_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637760,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674320,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1701",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/io_uring.c:io_file_data_ref_zero",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:fullbatt_handler",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_dad_failure",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674320,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654144,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1707",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/io_uring.c:io_file_data_ref_zero",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/xen/events/events_base.c:lateeoi_list_add",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654144,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660576,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1708",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/io_uring.c:io_rsrc_node_ref_zero",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660576,
      "name": "mod_delayed_work_on",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737664,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1738",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/io_uring.c:io_rsrc_node_ref_zero",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/disk-events.c:disk_flush_events",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737664,
      "name": "mod_delayed_work_on",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835696,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1728",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_flusher_threads",
        "fs/fs-writeback.c:wakeup_flusher_threads_bdi",
        "fs/fs-writeback.c:wb_workfn",
        "fs/fs-writeback.c:wb_start_background_writeback",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:wb_queue_work",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/disk-events.c:disk_flush_events",
        "io_uring/io_uring.c:io_rsrc_node_ref_zero",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/thermal_core.c:handle_thermal_trip",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835696,
      "name": "mod_delayed_work_on",
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980976,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1728",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:schedule_delayed_monitor_work",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/disk-events.c:disk_flush_events",
        "io_uring/rsrc.c:io_rsrc_node_ref_zero",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980976,
      "name": "mod_delayed_work_on",
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580030080,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1930",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:schedule_delayed_monitor_work",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/disk-events.c:disk_flush_events",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580030080,
      "name": "mod_delayed_work_on",
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072912,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:2016",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rcu/tree.c:schedule_delayed_monitor_work",
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/disk-events.c:disk_flush_events",
        "drivers/gpio/gpiolib-cdev.c:debounce_irq_handler",
        "drivers/gpio/gpiolib-cdev.c:process_hw_ts",
        "drivers/xen/events/events_base.c:xen_irq_lateeoi_worker",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr_work",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/gpu/drm/drm_probe_helper.c:drm_helper_probe_single_connector_modes",
        "drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_alter_state",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:_phy_state_machine",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/net/phy/phy.c:phy_ethtool_ksettings_set",
        "drivers/net/phy/phy.c:phy_start_cable_test_tdr",
        "drivers/net/phy/phy.c:phy_start_cable_test",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/thermal_core.c:thermal_pm_notify",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:decay_interval_set",
        "drivers/ras/cec.c:cec_work_fn",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_dad_kick",
        "net/ipv6/addrconf.c:addrconf_add_linklocal",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/mcast.c:mld_ifc_work",
        "net/ipv6/mcast.c:mld_dad_work",
        "net/ipv6/mcast.c:ipv6_mc_dad_complete",
        "net/ipv6/mcast.c:igmp6_event_report",
        "net/ipv6/mcast.c:__mld_query_work",
        "net/ipv6/mcast.c:igmp6_event_query",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072912,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490810704,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490810704,
      "name": "mod_delayed_work_on",
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224841272,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224841272,
      "name": "mod_delayed_work_on",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283631920,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "mm/backing-dev.c:wb_shutdown",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283631920,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271489412,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271489412,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579614064,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:cec_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579614064,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542992,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/acpi/nfit/core.c:scrub_show",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:cec_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542992,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611344,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:cec_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611344,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool mod_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "mod_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648000,
      "name": "mod_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1704",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup-v1.c:cgroup_pidlist_stop",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "fs/fs-writeback.c:dirtytime_interval_handler",
        "fs/fs-writeback.c:wb_queue_work",
        "fs/fs-writeback.c:wb_wakeup",
        "block/blk-core.c:kblockd_mod_delayed_work_on",
        "block/genhd.c:disk_flush_events",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:devcd_data_write",
        "drivers/net/phy/phy.c:phy_mac_interrupt",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_start",
        "drivers/net/phy/phy.c:phy_interrupt",
        "drivers/net/phy/phy.c:phy_error",
        "drivers/usb/host/xhci-ring.c:queue_command",
        "drivers/usb/host/xhci-ring.c:handle_cmd_completion",
        "drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start",
        "drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_mod_work",
        "drivers/ras/cec.c:cec_mod_work",
        "net/ipv6/addrconf.c:addrconf_init",
        "net/ipv6/addrconf.c:addrconf_verify_rtnl",
        "net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr",
        "net/ipv6/addrconf.c:addrconf_mod_dad_work",
        "net/strparser/strparser.c:__strp_recv",
        "net/strparser/strparser.c:__strp_recv",
        "net/rfkill/input.c:rfkill_schedule_global_op"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648000,
      "name": "mod_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
