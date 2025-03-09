# Function: <code>timer_delete_sync</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int timer_delete_sync(struct timer_list * timer)
```

```json
{
  "name": "timer_delete_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596490181,
      "name": "timer_delete_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1626",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "mm/backing-dev.c:bdi_unregister",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
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
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor",
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580774544,
      "name": "timer_delete_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int timer_delete_sync(struct timer_list * timer)
```

```json
{
  "name": "timer_delete_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597031493,
      "name": "timer_delete_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1626",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "mm/backing-dev.c:bdi_unregister",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
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
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor",
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857616,
      "name": "timer_delete_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
int timer_delete_sync(struct timer_list * timer)
```

```json
{
  "name": "timer_delete_sync",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597960885,
      "name": "timer_delete_sync",
      "external": true,
      "loc": "kernel/time/timer.c:1626",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/timer.c:schedule_timeout"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down",
        "arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/workqueue.c:flush_delayed_work",
        "kernel/workqueue.c:worker_thread",
        "kernel/kthread.c:__kthread_cancel_work_sync",
        "kernel/kthread.c:kthread_mod_delayed_work",
        "kernel/rcu/update.c:rcu_tasks_postscan",
        "kernel/rcu/srcutree.c:cleanup_srcu_struct",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files",
        "mm/page-writeback.c:wb_domain_exit",
        "mm/backing-dev.c:bdi_unregister",
        "fs/ext4/super.c:__ext4_fill_super",
        "fs/jbd2/journal.c:kjournald2",
        "fs/jbd2/journal.c:kjournald2",
        "block/blk-core.c:blk_sync_queue",
        "block/blk-stat.c:blk_stat_remove_callback",
        "block/blk-throttle.c:blk_throtl_exit",
        "block/blk-throttle.c:throtl_pd_free",
        "block/blk-wbt.c:wbt_disable_default",
        "drivers/tty/vt/vt.c:do_blank_screen",
        "drivers/tty/serial/8250/8250_core.c:univ8250_release_irq",
        "drivers/tty/serial/sccnxp.c:sccnxp_remove",
        "drivers/char/random.c:try_to_generate_entropy",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_release",
        "drivers/char/tpm/tpm-dev-common.c:tpm_common_read",
        "drivers/iommu/dma-iommu.c:iommu_put_dma_cookie",
        "drivers/base/power/wakeup.c:wakeup_source_remove",
        "drivers/ata/libata-eh.c:ata_scsi_port_error_handler",
        "drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release",
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
        "drivers/md/md.c:mddev_suspend",
        "drivers/mmc/core/host.c:mmc_retune_timer_stop",
        "drivers/mmc/core/host.c:mmc_retune_disable",
        "drivers/leds/led-core.c:led_blink_set",
        "drivers/leds/led-core.c:set_brightness_delayed",
        "net/core/gen_estimator.c:gen_new_estimator",
        "net/core/neighbour.c:neigh_table_clear",
        "net/core/drop_monitor.c:net_dm_trace_off_set",
        "net/core/drop_monitor.c:net_dm_trace_on_set",
        "net/core/drop_monitor.c:net_dm_hw_monitor_stop",
        "net/core/drop_monitor.c:net_dm_hw_monitor_start",
        "net/ipv4/inet_timewait_sock.c:inet_twsk_purge",
        "net/ipv4/inet_fragment.c:inet_frags_free_cb",
        "net/xfrm/xfrm_state.c:___xfrm_state_destroy",
        "net/ipv6/ip6_fib.c:fib6_net_exit",
        "net/packet/af_packet.c:packet_set_ring",
        "net/ncsi/ncsi-manage.c:ncsi_free_request",
        "net/ncsi/ncsi-manage.c:ncsi_stop_channel_monitor",
        "net/mctp/af_mctp.c:mctp_sk_unhash"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580947776,
      "name": "timer_delete_sync",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int timer_delete_sync(struct timer_list * timer)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
