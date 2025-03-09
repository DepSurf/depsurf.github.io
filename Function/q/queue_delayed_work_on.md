# Function: <code>queue_delayed_work_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470528,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1491",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_notify",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcu.c:call_srcu",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:setup_vmstat",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "block/blk-core.c:blk_delay_queue",
        "block/blk-core.c:kblockd_schedule_delayed_work",
        "block/blk-core.c:kblockd_schedule_delayed_work_on",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:disk_check_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/phy/phy.c:phy_start_machine",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/power/charger-manager.c:_setup_polling",
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "net/core/dst.c:dst_gc_task",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/ipv4/inetpeer.c:inetpeer_gc_worker",
        "net/ipv4/inetpeer.c:inetpeer_inval_rcu",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:devinet_init",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470528,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579484288,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1547",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcu.c:call_srcu",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "block/blk-core.c:kblockd_schedule_delayed_work_on",
        "block/blk-core.c:kblockd_schedule_delayed_work",
        "block/blk-core.c:blk_delay_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_change",
        "drivers/net/phy/phy.c:phy_start_machine",
        "drivers/net/virtio_net.c:virtnet_restore",
        "drivers/net/virtio_net.c:virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:virtnet_receive",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/power_supply_core.c:__power_supply_register",
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/power/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/dst.c:dst_gc_task",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/inetpeer.c:inetpeer_inval_rcu",
        "net/ipv4/inetpeer.c:inetpeer_gc_worker",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484288,
      "name": "queue_delayed_work_on",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579504864,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1549",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/intel/cqm.c:intel_cqm_event_init",
        "arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcu.c:call_srcu",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:setup_vmstat",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_add_mark_locked",
        "block/blk-core.c:kblockd_schedule_delayed_work_on",
        "block/blk-core.c:kblockd_schedule_delayed_work",
        "block/blk-core.c:blk_delay_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy.c:phy_start_machine",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/dst.c:dst_gc_task",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/inetpeer.c:inetpeer_inval_rcu",
        "net/ipv4/inetpeer.c:inetpeer_gc_worker",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579504864,
      "name": "queue_delayed_work_on",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493904,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1548",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "block/blk-core.c:kblockd_schedule_delayed_work_on",
        "block/blk-core.c:kblockd_schedule_delayed_work",
        "block/blk-core.c:blk_delay_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/regulator/core.c:regulator_disable_deferred",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy.c:phy_start_machine",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/inetpeer.c:inetpeer_inval_rcu",
        "net/ipv4/inetpeer.c:inetpeer_gc_worker",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493904,
      "name": "queue_delayed_work_on",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579520624,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1549",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/blk-core.c:kblockd_schedule_delayed_work_on",
        "block/blk-core.c:kblockd_schedule_delayed_work",
        "block/blk-core.c:blk_delay_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy.c:phy_start_machine",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/watchdog/watchdog_dev.c:watchdog_dev_register",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579520624,
      "name": "queue_delayed_work_on",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551552,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1547",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/blk-core.c:blk_delay_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/phy/phy.c:phy_state_machine",
        "drivers/net/phy/phy.c:phy_trigger_machine",
        "drivers/net/phy/phy.c:phy_start_machine",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551552,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579588176,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1567",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/hpet.c:hpet_cpuhp_online",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/rcu/srcutree.c:srcu_queue_delayed_work_on",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/xen-selfballoon.c:xen_selfballoon_init",
        "drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking",
        "drivers/xen/xen-selfballoon.c:store_selfballooning",
        "drivers/xen/xen-selfballoon.c:selfballoon_process",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579588176,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579612480,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1663",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:nvdimm_security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/xdp.c:xdp_rxq_info_unreg_mem_model",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612480,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637680,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637680,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579673776,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1663",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kfree_rcu_scheduler_running",
        "kernel/rcu/tree.c:kfree_rcu_shrink_scan",
        "kernel/rcu/tree.c:kfree_call_rcu",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/vmstat.c:start_shepherd_timer",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/io_uring.c:io_file_data_ref_zero",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579673776,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653600,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1669",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/mce/therm_throt.c:throttle_active_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kfree_rcu_scheduler_running",
        "kernel/rcu/tree.c:kfree_rcu_shrink_scan",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/vmstat.c:start_shepherd_timer",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/io_uring.c:io_file_data_ref_zero",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653600,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579660000,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1670",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kfree_rcu_scheduler_running",
        "kernel/rcu/tree.c:kfree_rcu_shrink_scan",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579660000,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579737104,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1700",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/reboot.c:hw_protection_shutdown",
        "kernel/sched/psi.c:psi_group_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kfree_rcu_scheduler_running",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:schedule_page_work_fn",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:optimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/kfence/core.c:kfence_init",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/io_uring.c:io_req_task_work_add",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events",
        "block/disk-events.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_resume",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579737104,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579835600,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1690",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/reboot.c:hw_protection_shutdown",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kfree_rcu_scheduler_running",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:schedule_page_work_fn",
        "kernel/rcu/tree.c:kfree_rcu_monitor",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:optimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events",
        "block/disk-events.c:__disk_unblock_events",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_managed_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devl_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579835600,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980832,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1690",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:schedule_page_work_fn",
        "kernel/rcu/tree.c:schedule_delayed_monitor_work",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:optimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events",
        "block/disk-events.c:__disk_unblock_events",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/char/random.c:crng_reseed",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_acquire_i2c_bus",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_managed_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:__devlink_port_type_set",
        "net/core/devlink.c:devl_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980832,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029936,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1892",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:schedule_page_work_fn",
        "kernel/rcu/tree.c:schedule_delayed_monitor_work",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:optimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events",
        "block/disk-events.c:__disk_unblock_events",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/char/random.c:crng_reseed",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_managed_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_write_space",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/devlink/leftover.c:__devlink_port_type_set",
        "net/devlink/leftover.c:devl_port_register_with_ops",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029936,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580072768,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1978",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/intel.c:split_lock_warn",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:sched_tick_remote",
        "kernel/sched/build_utility.c:psi_group_change",
        "kernel/sched/build_utility.c:psi_avgs_work",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:srcu_funnel_gp_start",
        "kernel/rcu/tree.c:kvfree_call_rcu",
        "kernel/rcu/tree.c:schedule_page_work_fn",
        "kernel/rcu/tree.c:schedule_delayed_monitor_work",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/kprobes.c:optimize_kprobe",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:unaccount_event",
        "kernel/jump_label.c:__static_key_slow_dec_deferred",
        "mm/page-writeback.c:__folio_end_writeback",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "mm/kfence/core.c:kfence_init_enable",
        "mm/kfence/core.c:param_set_sample_interval",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:flush_memcg_stats_dwork",
        "mm/page_reporting.c:page_reporting_register",
        "mm/page_reporting.c:page_reporting_process",
        "mm/page_reporting.c:__page_reporting_notify",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "fs/fuse/dax.c:fuse_dax_free_mem_worker",
        "fs/fuse/dax.c:alloc_dax_mapping",
        "security/integrity/ima/ima_queue_keys.c:ima_init_key_queue",
        "block/disk-events.c:disk_check_events",
        "block/disk-events.c:__disk_unblock_events",
        "block/disk-events.c:__disk_unblock_events",
        "io_uring/io_uring.c:io_fallback_tw",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_startup",
        "drivers/video/fbdev/core/fbcon.c:set_con2fb_map",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/regulator/irq_helpers.c:regulator_notifier_isr",
        "drivers/char/random.c:crng_reseed",
        "drivers/iommu/iova.c:iova_depot_work_func",
        "drivers/iommu/iova.c:free_iova_fast",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/dd.c:deferred_probe_extend_timeout",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/nvdimm/security.c:security_overwrite",
        "drivers/scsi/scsi_error.c:scsi_timeout",
        "drivers/ata/libata-scsi.c:ata_scsi_dev_rescan",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_bmdma_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_qc_issue",
        "drivers/ata/libata-sff.c:ata_sff_pio_task",
        "drivers/gpu/drm/drm_probe_helper.c:output_poll_execute",
        "drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_reschedule",
        "drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_enable",
        "drivers/net/virtio_net.c:virtnet_set_ringparam",
        "drivers/net/virtio_net.c:_virtnet_set_queues",
        "drivers/net/virtio_net.c:virtnet_open",
        "drivers/net/virtio_net.c:refill_work",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/host/ehci-platform.c:quirk_poll_timer",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/power/supply/power_supply_core.c:__power_supply_register",
        "drivers/power/supply/charger-manager.c:charger_extcon_work",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/thermal/intel/therm_throt.c:throttle_active_work",
        "drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_update_interval",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_managed_work",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/link_watch.c:linkwatch_schedule_work",
        "net/core/page_pool.c:page_pool_release_retry",
        "net/core/netpoll.c:__netpoll_send_skb",
        "net/core/netpoll.c:queue_process",
        "net/core/skmsg.c:sk_psock_write_space",
        "net/core/skmsg.c:sk_psock_verdict_apply",
        "net/core/skmsg.c:sk_psock_skb_redirect",
        "net/core/skmsg.c:sk_psock_backlog",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/ipv4/nexthop.c:nh_res_table_upkeep",
        "net/ipv6/mcast.c:mld_report_work",
        "net/ipv6/mcast.c:mld_query_work",
        "net/devlink/core.c:devlink_rel_nested_in_notify_work_schedule",
        "net/devlink/core.c:devlink_rel_nested_in_notify_work",
        "net/devlink/port.c:__devlink_port_type_set",
        "net/devlink/port.c:devl_port_register_with_ops",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/core.c:rfkill_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580072768,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490810504,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/amba/bus.c:amba_deferred_retry_func",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490810504,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224841164,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:srcu_reschedule",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/bus/ti-sysc.c:sysc_probe",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/amba/bus.c:amba_deferred_retry_func",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init",
        "drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep",
        "drivers/auxdisplay/arm-charlcd.c:charlcd_probe",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_irq_work",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_core.c:musb_stage0_irq",
        "drivers/usb/musb/musb_virthub.c:musb_port_reset",
        "drivers/usb/musb/musb_virthub.c:musb_port_reset",
        "drivers/usb/musb/musb_virthub.c:musb_port_reset",
        "drivers/usb/musb/musb_virthub.c:musb_port_suspend",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_stop",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_pullup",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_disable",
        "drivers/usb/musb/musb_gadget.c:musb_gadget_enable",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "sound/core/compress_offload.c:snd_compr_stop_error",
        "sound/soc/soc-jack.c:snd_soc_jack_add_gpios",
        "sound/soc/soc-jack.c:gpio_handler",
        "sound/soc/soc-pcm.c:soc_pcm_close",
        "sound/soc/soc-compress.c:soc_compr_free",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224841164,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283628784,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan_init",
        "arch/powerpc/kernel/rtasd.c:rtas_event_scan",
        "arch/powerpc/platforms/pseries/lpar.c:dtl_worker_online",
        "arch/powerpc/platforms/pseries/lpar.c:process_dtl_buffer",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_sg",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_page",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_page",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_free_coherent",
        "arch/powerpc/platforms/pseries/vio.c:vio_cmo_entitlement_update",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/tty/hvc/hvsi.c:hvsi_write",
        "drivers/tty/hvc/hvsi.c:hvsi_write_worker",
        "drivers/tty/hvc/hvsi.c:hvsi_write_worker",
        "drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers",
        "drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers",
        "drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers",
        "drivers/scsi/scsi_transport_srp.c:srp_reconnect_work",
        "drivers/scsi/scsi_transport_srp.c:store_reconnect_delay",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_pm_notify",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283628784,
      "name": "queue_delayed_work_on",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271485502,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/time/ntp.c:sync_hw_clock",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_start_host",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:mmc_detect_card_removed",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271485502,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613984,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/nvme/host/core.c:nvme_keep_alive_end_io",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613984,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542944,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/core.c:sched_cpu_starting",
        "kernel/sched/core.c:sched_tick_remote",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/acpi/nfit/core.c:__sched_ars",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete",
        "drivers/nvme/host/core.c:nvme_keep_alive_end_io",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542944,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579611264,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start",
        "net/netfilter/nf_conntrack_core.c:gc_worker",
        "net/netfilter/nf_conntrack_ecache.c:ecache_work",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611264,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
bool queue_delayed_work_on(int cpu, struct workqueue_struct * wq, struct delayed_work * dwork, long unsigned int delay)
```

```json
{
  "name": "queue_delayed_work_on",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579649984,
      "name": "queue_delayed_work_on",
      "external": true,
      "loc": "kernel/workqueue.c:1666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr",
        "arch/x86/kernel/tsc.c:init_tsc_clocksource",
        "arch/x86/kernel/tsc.c:tsc_refine_calibration_work",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:mbm_handle_overflow",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler",
        "arch/x86/kernel/cpu/resctrl/monitor.c:cqm_handle_limbo",
        "arch/x86/kernel/check.c:start_periodic_check_for_corruption",
        "arch/x86/kernel/check.c:check_corruption",
        "kernel/sched/psi.c:psi_task_change",
        "kernel/sched/psi.c:psi_avgs_work",
        "kernel/power/qos.c:pm_qos_update_request_timeout",
        "kernel/rcu/srcutree.c:__call_srcu",
        "kernel/livepatch/transition.c:klp_try_complete_transition",
        "kernel/time/ntp.c:ntp_notify_cmos_timer",
        "kernel/kprobes.c:kprobe_optimizer",
        "kernel/events/core.c:_free_event",
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/backing-dev.c:wb_wakeup_delayed",
        "fs/namespace.c:mntput_no_expire",
        "fs/fs-writeback.c:start_dirtytime_writeback",
        "fs/fs-writeback.c:wakeup_dirtytime_writeback",
        "fs/notify/mark.c:fsnotify_put_mark",
        "block/genhd.c:disk_check_events",
        "block/genhd.c:__disk_unblock_events",
        "block/genhd.c:__disk_unblock_events",
        "drivers/pci/pci.c:pci_pme_active",
        "drivers/pci/pci.c:pci_pme_list_scan",
        "drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press",
        "drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite",
        "drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync",
        "drivers/xen/grant-table.c:__gnttab_unmap_refs_async",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:balloon_set_new_target",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/regulator/core.c:regulator_init_complete",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/base/devcoredump.c:dev_coredumpm",
        "drivers/block/xen-blkfront.c:blkfront_delay_work",
        "drivers/block/xen-blkfront.c:blkfront_gather_backend_features",
        "drivers/nvdimm/security.c:nvdimm_security_store",
        "drivers/nvdimm/security.c:__nvdimm_security_overwrite_query",
        "drivers/scsi/scsi_error.c:scsi_times_out",
        "drivers/ata/libata-scsi.c:ata_scsi_scan_host",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-sff.c:ata_sff_queue_pio_task",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_port_connect",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:hub_activate",
        "drivers/usb/core/hub.c:led_work",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_start",
        "drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr",
        "drivers/input/input-poller.c:input_dev_poller_queue_work",
        "drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work",
        "drivers/input/keyboard/atkbd.c:atkbd_event_work",
        "drivers/media/cec/cec-adap.c:cec_transmit_done_ts",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:_setup_polling",
        "drivers/edac/wq.c:edac_queue_work",
        "drivers/mmc/core/core.c:mmc_rescan",
        "drivers/mmc/core/core.c:_mmc_detect_change",
        "drivers/mmc/core/sdio.c:mmc_sdio_resume",
        "drivers/mmc/core/sdio_irq.c:sdio_signal_irq",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_interval_update",
        "drivers/devfreq/devfreq.c:devfreq_monitor_resume",
        "drivers/devfreq/devfreq.c:devfreq_monitor_start",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/ras/cec.c:cec_init",
        "net/core/neighbour.c:neigh_table_init",
        "net/core/neighbour.c:neigh_periodic_work",
        "net/core/netpoll.c:netpoll_send_skb_on_dev",
        "net/core/netpoll.c:queue_process",
        "net/core/devlink.c:devlink_port_type_clear",
        "net/core/devlink.c:devlink_port_register",
        "net/ipv4/devinet.c:devinet_init",
        "net/ipv4/devinet.c:inet_rtm_newaddr",
        "net/ipv4/devinet.c:check_lifetime",
        "net/ipv4/devinet.c:__inet_insert_ifa",
        "net/rfkill/core.c:rfkill_register",
        "net/rfkill/core.c:rfkill_poll",
        "net/rfkill/input.c:rfkill_schedule_ratelimited"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579649984,
      "name": "queue_delayed_work_on",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
