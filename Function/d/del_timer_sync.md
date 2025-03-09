# Function: <code>del_timer_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579813312,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1103",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/relay.c:__relay_reset",
        "kernel/relay.c:relay_close_buf",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-throttle.c:throtl_pd_free",
        "block/cfq-iosched.c:cfq_exit_queue",
        "block/cfq-iosched.c:cfq_exit_queue",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_cursor",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_read",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_init",
        "drivers/cpufreq/intel_pstate.c:intel_pstate_stop_cpu",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/flow.c:flow_cache_fini",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579813312,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579843728,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1244",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_callback",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/relay.c:relay_close_buf",
        "kernel/relay.c:__relay_reset",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-throttle.c:throtl_pd_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_cursor",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_read",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-mem.c:xhci_mem_cleanup",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/flow.c:flow_cache_fini",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579843728,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579872496,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1254",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-wbt.c:wbt_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_cursor",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev.c:tpm_release",
        "drivers/char/tpm/tpm-dev.c:tpm_read",
        "drivers/base/power/wakeup.c:wakeup_source_destroy",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/flow.c:flow_cache_fini",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/ipmr.c:ipmr_net_exit",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579872496,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579881520,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1227",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/video/console/fbcon.c:fbcon_blank",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_switch",
        "drivers/video/console/fbcon.c:fbcon_cursor",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/video/console/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_ifdown",
        "net/core/flow.c:flow_cache_fini",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579881520,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579924496,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1265",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_release_ctrl",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:__tun_chr_ioctl",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_ifdown",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579924496,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579972288,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1273",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:neigh_ifdown",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:xfrm_state_gc_task",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579972288,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014048,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1272",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014048,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1267",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "kernel/padata.c:padata_flush_queues",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580070337,
      "name": "del_timer_sync.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071580062320,
      "name": "del_timer_sync",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111376,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111376,
      "name": "del_timer_sync",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580173232,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1354",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:maybe_create_worker",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_rules_exit",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_stop_dev",
        "net/ncsi/ncsi-manage.c:ncsi_kick_channels",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_remove_package",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580173232,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158272,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1348",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:maybe_create_worker",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/sock.c:sk_stop_timer_sync",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_connection_sock.c:reqsk_queue_unlink",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_rules_exit",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_stop_dev",
        "net/ncsi/ncsi-manage.c:ncsi_kick_channels",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_remove_package",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor",
        "net/ncsi/ncsi-manage.c:ncsi_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158272,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580162960,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1366",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/sock.c:sk_stop_timer_sync",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_rules_exit",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_reset_dev",
        "net/ncsi/ncsi-manage.c:ncsi_stop_dev",
        "net/ncsi/ncsi-manage.c:ncsi_kick_channels",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_remove_package"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580162960,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580307456,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1352",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "mm/backing-dev.c:bdi_unregister",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_exit",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/sock.c:sk_stop_timer_sync",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_rules_exit",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580307456,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580519472,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1405",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:set_ignore_ce",
        "arch/x86/kernel/cpu/mce/core.c:set_bank",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "mm/backing-dev.c:bdi_unregister",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/block/loop.c:lo_free_disk",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_net_init",
        "drivers/net/xen-netfront.c:xennet_disconnect_backend",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_rules_exit",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_rules_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor",
        "net/mctp/af_mctp.c:mctp_sk_close"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580519472,
      "name": "del_timer_sync",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "del_timer_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579335877,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579959442,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580013668,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580603754,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596490181,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580959976,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424613,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_domain_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582611773,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584924370,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585040715,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585370393,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "fs/pstore/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586396165,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_sync_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586499129,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_remove_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586618154,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586685068,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_disable_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589725125,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589755971,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_blank_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589832517,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/serial/8250/8250_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589904962,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589940716,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590010987,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590211855,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590411542,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591145676,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591348811,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591449051,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591527348,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_quiesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591548741,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/core/hcd.c:usb_stop_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591757493,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591840747,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591861990,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591893288,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591924493,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592009406,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592124156,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:__input_unregister_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592461586,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592787333,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/mmc/core/host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592863925,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593104925,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593208958,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/gen_estimator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_estimator.c:gen_new_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593369472,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_table_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593673776,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594206328,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594216836,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594615125,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frags_free_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594806463,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595074805,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_net_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595391166,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595527975,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595691827,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "del_timer_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579344757,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580028054,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067204,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580661401,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_postscan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677962,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597031493,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581047421,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582629829,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_domain_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582820557,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585152541,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585268219,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585600857,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "fs/pstore/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586642981,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_sync_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586746745,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_remove_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586876351,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586946496,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_disable_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590029973,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590060835,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_blank_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590141877,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/serial/8250/8250_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590214131,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590249996,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590320235,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590533375,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590731126,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591504109,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591710539,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591864555,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591949234,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_quiesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591970357,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/core/hcd.c:usb_stop_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592180789,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592263675,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592284918,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592316664,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592347199,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592430039,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592547532,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:__input_unregister_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592886242,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593223717,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/mmc/core/host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593301589,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593560269,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593669198,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/gen_estimator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_estimator.c:gen_new_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593831648,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_table_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594154356,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594593360,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594604036,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595007109,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frags_free_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595198891,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595468549,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_net_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595788362,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596036519,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596203251,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:198",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "del_timer_sync",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579375333,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067142,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580109844,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727113,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "kernel/rcu/update.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/update.c:rcu_tasks_postscan"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580744634,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "kernel/rcu/srcutree.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/rcu/srcutree.c:cleanup_srcu_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597960885,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "kernel/time/timer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581144453,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582801061,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:wb_domain_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995261,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:bdi_unregister"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385090,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "fs/ext4/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/ext4/super.c:__ext4_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585501643,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "fs/jbd2/journal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585846793,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "fs/pstore/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586913941,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_sync_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587018975,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "block/blk-stat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-stat.c:blk_stat_remove_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587154255,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587226931,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "block/blk-wbt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-wbt.c:wbt_disable_default"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590368549,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/tty/vt/keyboard.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590400003,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_blank_screen"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590481845,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/tty/serial/8250/8250_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590554831,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/tty/serial/sccnxp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/sccnxp.c:sccnxp_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590590988,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/char/random.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/random.c:try_to_generate_entropy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590661579,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590889072,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591093046,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/base/power/wakeup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/power/wakeup.c:wakeup_source_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591852873,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/ata/libata-eh.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592167777,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/gpu/drm/drm_vblank.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592454827,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/net/tun.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/net/tun.c:tun_net_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592604360,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/net/xen-netfront.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/xen-netfront.c:xennet_disconnect_backend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592689058,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/core/hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hub.c:hub_quiesce"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592710197,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_stop_hcd",
        "drivers/usb/core/hcd.c:usb_stop_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592921477,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593004763,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_suspend",
        "drivers/usb/host/ehci-platform.c:ehci_platform_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593026230,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/host/ohci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593058056,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/host/uhci-hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/uhci-hcd.c:uhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593088916,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593173711,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/usb/host/xhci-hub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593291980,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/input/input.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/input/input.c:__input_unregister_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593647129,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:mddev_suspend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593978565,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/mmc/core/host.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594057989,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "drivers/leds/led-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594328957,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/core/sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594447293,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/core/gen_estimator.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/gen_estimator.c:gen_new_estimator"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594613248,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/core/neighbour.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/neighbour.c:neigh_table_clear"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594950820,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/core/drop_monitor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595396952,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/ipv4/inet_timewait_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595407716,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/ipv4/inet_connection_sock.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595819781,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/ipv4/inet_fragment.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv4/inet_fragment.c:inet_frags_free_cb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596039451,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/xfrm/xfrm_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596310869,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/ipv6/ip6_fib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ipv6/ip6_fib.c:fib6_net_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596638850,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/packet/af_packet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/packet/af_packet.c:packet_set_ring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596901191,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597081011,
      "name": "del_timer_sync",
      "external": false,
      "loc": "include/linux/timer.h:183",
      "file": "net/mctp/af_mctp.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491330840,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491330840,
      "name": "del_timer_sync",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225319252,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_del_cursor_timer",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/amba-pl011.c:pl011_shutdown",
        "drivers/tty/serial/imx.c:imx_uart_set_termios",
        "drivers/tty/serial/imx.c:imx_uart_shutdown",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_stop",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/host/sdhci.c:sdhci_remove_host",
        "drivers/mmc/host/sdhci.c:sdhci_remove_host",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "sound/core/timer.c:snd_timer_s_close",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225319252,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284253008,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_del_cursor_timer",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/tun.c:tun_free_netdev",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_stop_cpu",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284253008,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271826782,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:fbcon_del_cursor_timer",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271826782,
      "name": "del_timer_sync",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080576,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/nvme/host/multipath.c:nvme_mpath_stop",
        "drivers/nvme/host/multipath.c:nvme_read_ana_log",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080576,
      "name": "del_timer_sync",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025392,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/nvme/host/multipath.c:nvme_mpath_stop",
        "drivers/nvme/host/multipath.c:nvme_read_ana_log",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/net/vxlan.c:vxlan_stop",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025392,
      "name": "del_timer_sync",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071648,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071648,
      "name": "del_timer_sync",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int del_timer_sync(struct timer_list * timer)
```

```json
{
  "name": "del_timer_sync",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580122464,
      "name": "del_timer_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1342",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "arch/x86/kernel/pci-calgary_64.c:calgary_iommu_init",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/time/timer.c:schedule_timeout",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "fs/pstore/platform.c:pstore_unregister",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-core.c:blk_cleanup_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-iocost.c:ioc_rqos_exit",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/video/fbdev/core/fbcon.c:store_cursor_blink",
        "drivers/video/fbdev/core/fbcon.c:fbcon_blank",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_switch",
        "drivers/video/fbdev/core/fbcon.c:fbcon_cursor",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/video/fbdev/core/fbcon.c:fbcon_deinit",
        "drivers/acpi/apei/ghes.c:ghes_remove",
        "drivers/tty/sysrq.c:sysrq_disconnect",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/usb/core/hub.c:hub_quiesce",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free",
        "drivers/usb/host/ohci-hcd.c:ohci_stop",
        "drivers/usb/host/ohci-hcd.c:ohci_bus_suspend",
        "drivers/usb/host/uhci-hcd.c:uhci_stop",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_suspend",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/input/input.c:__input_unregister_device",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:level_store",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_stop_software_blink",
        "drivers/leds/led-core.c:led_blink_set",
        "net/core/gen_estimator.c:gen_kill_estimator",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/neighbour.c:__neigh_ifdown",
        "net/core/drop_monitor.c:net_dm_cmd_trace",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/ipv4/ipmr.c:ipmr_free_table",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/ipv6/ip6mr.c:ip6mr_free_table",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580122464,
      "name": "del_timer_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int del_timer_sync(struct timer_list * timer)
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
