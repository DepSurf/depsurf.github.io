# Function: <code>cancel_delayed_work_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480736,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:2921",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpuup_callback",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/charger-manager.c:charger_manager_remove",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/cpufreq/cpufreq_ondemand.c:update_sampling_rate",
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "net/core/neighbour.c:neigh_table_clear",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480736,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494560,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3021",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpuup_callback",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/power_supply_core.c:power_supply_unregister",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:charger_manager_remove",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494560,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513984,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3047",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513984,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502480,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3046",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502480,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528496,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3060",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528496,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556256,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3134",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556256,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579593872,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3157",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579593872,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619568,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3257",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619568,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643248,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643248,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579674912,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3263",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "kernel/sched/psi.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579674912,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579654736,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3269",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "arch/x86/kernel/cpu/mce/therm_throt.c:thermal_throttle_offline",
        "kernel/sched/psi.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "block/genhd.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579654736,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579661184,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3270",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-sysfs.c:blk_release_queue",
        "block/blk-sysfs.c:blk_release_queue",
        "block/genhd.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579661184,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579738272,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3309",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/disk-events.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:linereq_free",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/core.c:rfkill_pause_polling",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579738272,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579841664,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3292",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/disk-events.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devl_port_unregister",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579841664,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978512,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3299",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/disk-events.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devl_port_unregister",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978512,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580028592,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3615",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/disk-events.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_lastclose",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_map_close",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/devlink/leftover.c:__devlink_port_type_set",
        "net/devlink/leftover.c:devl_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028592,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580067648,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3636",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_cgroup_free",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "mm/page_reporting.c:page_reporting_unregister",
        "fs/fuse/dax.c:fuse_dax_cancel_work",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/blk-mq.c:blk_mq_cancel_work_sync",
        "block/disk-events.c:disk_block_events",
        "drivers/gpio/gpiolib-cdev.c:edge_detector_stop",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_release",
        "drivers/regulator/irq_helpers.c:regulator_irq_helper_cancel",
        "drivers/iommu/iova.c:free_iova_rcaches",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/nvdimm/dimm_devs.c:nvdimm_delete",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_port_detach",
        "drivers/ata/libata-core.c:ata_sas_port_suspend",
        "drivers/ata/libata-core.c:ata_port_runtime_suspend",
        "drivers/ata/libata-core.c:ata_port_pm_freeze",
        "drivers/ata/libata-core.c:ata_port_pm_suspend",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_cleanup",
        "drivers/net/phy/phy.c:phy_stop",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/virtio_net.c:virtnet_probe",
        "drivers/net/virtio_net.c:virtnet_close",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/thermal/intel/therm_throt.c:thermal_throttle_offline",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/host.c:devm_mmc_host_release",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/skmsg.c:sk_psock_destroy",
        "net/core/sock_map.c:sock_map_close",
        "net/ipv4/nexthop.c:replace_nexthop_grp_res",
        "net/ipv6/addrconf.c:addrconf_exit_net",
        "net/ipv6/mcast.c:ipv6_mc_down",
        "net/devlink/port.c:__devlink_port_type_set",
        "net/devlink/port.c:devl_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580067648,
      "name": "cancel_delayed_work_sync",
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490809128,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_stop",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490809128,
      "name": "cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224845260,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/bus/ti-sysc.c:sysc_remove",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_stop",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "sound/core/compress_offload.c:snd_compr_free",
        "sound/soc/soc-compress.c:soc_compr_set_params",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224845260,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283646432,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtasd.c:rtas_cancel_event_scan",
        "arch/powerpc/platforms/pseries/lpar.c:dtl_worker_offline",
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/tty/hvc/hvsi.c:hvsi_close",
        "drivers/scsi/scsi_transport_srp.c:srp_stop_rport_timers",
        "drivers/scsi/scsi_transport_srp.c:srp_stop_rport_timers",
        "drivers/scsi/scsi_transport_srp.c:srp_stop_rport_timers",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_unregister",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/core.c:rfkill_pause_polling",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283646432,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271489906,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271489906,
      "name": "cancel_delayed_work_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579619552,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/nvme/host/core.c:nvme_stop_ctrl",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619552,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579547920,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/acpi/nfit/core.c:acpi_nfit_shutdown",
        "drivers/nvme/host/core.c:nvme_stop_ctrl",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547920,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616832,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_end",
        "net/netfilter/nf_conntrack_ecache.c:nf_conntrack_ecache_pernet_fini",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616832,
      "name": "cancel_delayed_work_sync",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
bool cancel_delayed_work_sync(struct delayed_work * dwork)
```

```json
{
  "name": "cancel_delayed_work_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579648592,
      "name": "cancel_delayed_work_sync",
      "external": true,
      "loc": "kernel/workqueue.c:3266",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_cgroup_free",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "mm/vmstat.c:vmstat_cpu_down_prep",
        "block/blk-sysfs.c:__blk_release_queue",
        "block/blk-mq-sysfs.c:blk_mq_hw_sysfs_release",
        "block/genhd.c:disk_block_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/block/xen-blkfront.c:xlblk_exit",
        "drivers/ata/libata-core.c:ata_host_detach",
        "drivers/ata/libata-sff.c:ata_sff_flush_pio_task",
        "drivers/net/phy/phy.c:phy_stop_machine",
        "drivers/net/phy/phy_device.c:phy_remove",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/input/input-poller.c:input_dev_set_poll_interval",
        "drivers/input/input-poller.c:input_dev_poller_stop",
        "drivers/input/keyboard/atkbd.c:atkbd_disconnect",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg_fh",
        "drivers/power/supply/power_supply_core.c:power_supply_unregister",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:charger_manager_remove",
        "drivers/edac/wq.c:edac_stop_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_stop_host",
        "drivers/mmc/core/sdio.c:mmc_sdio_suspend",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_suspend",
        "drivers/devfreq/devfreq.c:devfreq_monitor_stop",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devlink_port_unregister",
        "net/strparser/strparser.c:strp_done",
        "net/rfkill/core.c:rfkill_suspend",
        "net/rfkill/input.c:rfkill_handler_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579648592,
      "name": "cancel_delayed_work_sync",
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
