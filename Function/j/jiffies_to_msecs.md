# Function: <code>jiffies_to_msecs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579806624,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:253",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/scsi_ioctl.c:sg_io",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/bsg.c:bsg_rq_end_io",
        "block/deadline-iosched.c:deadline_write_expire_show",
        "block/deadline-iosched.c:deadline_read_expire_show",
        "block/cfq-iosched.c:cfq_target_latency_show",
        "block/cfq-iosched.c:cfq_group_idle_show",
        "block/cfq-iosched.c:cfq_slice_idle_show",
        "block/cfq-iosched.c:cfq_slice_async_show",
        "block/cfq-iosched.c:cfq_slice_sync_show",
        "block/cfq-iosched.c:cfq_fifo_expire_async_show",
        "block/cfq-iosched.c:cfq_fifo_expire_sync_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_close",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/base/power/sysfs.c:rtpm_active_time_show",
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/md/bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579806624,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579834432,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:253",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/bsg.c:bsg_rq_end_io",
        "block/deadline-iosched.c:deadline_write_expire_show",
        "block/deadline-iosched.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_close",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/charger-manager.c:cm_suspend_complete",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/power/charger-manager.c:cm_suspend_prepare",
        "drivers/md/bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834432,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579863488,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:253",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/bsg.c:bsg_rq_end_io",
        "block/deadline-iosched.c:deadline_write_expire_show",
        "block/deadline-iosched.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579863488,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871712,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:343",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_rq_end_io",
        "block/deadline-iosched.c:deadline_write_expire_show",
        "block/deadline-iosched.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871712,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915120,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:309",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_rq_end_io",
        "block/deadline-iosched.c:deadline_write_expire_show",
        "block/deadline-iosched.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest",
        "drivers/base/power/sysfs.c:rtpm_suspended_time_show",
        "drivers/base/power/sysfs.c:rtpm_active_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915120,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579959680,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:310",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/bsg.c:bsg_rq_end_io",
        "block/deadline-iosched.c:deadline_write_expire_show",
        "block/deadline-iosched.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm-interface.c:tpm_do_selftest",
        "drivers/base/power/sysfs.c:runtime_suspended_time_show",
        "drivers/base/power/sysfs.c:runtime_active_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_timer.c:tcp_write_timer_handler",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959680,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580006336,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:308",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/base/power/sysfs.c:runtime_suspended_time_show",
        "drivers/base/power/sysfs.c:runtime_active_time_show",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580006336,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580049904,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049904,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098960,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098960,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161536,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cdrom_send_packet",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_fill_request_table",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161536,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580145680,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cdrom_send_packet",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_fill_request_table",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf",
        "net/ipv6/addrconf.c:ipv6_store_devconf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580145680,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580150368,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cdrom_send_packet",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/thermal/gov_power_allocator.c:pid_controller",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580150368,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294896,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/thermal/gov_power_allocator.c:pid_controller",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294896,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580503568,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/mq-deadline.c:deadline_prio_aging_expire_show",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_release_i2c_bus",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/thermal/gov_power_allocator.c:pid_controller",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580503568,
      "name": "jiffies_to_msecs",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580756784,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:show_min_ttl",
        "mm/mprotect.c:change_pte_range",
        "mm/page_alloc.c:memmap_init_zone_device",
        "mm/huge_memory.c:change_huge_pmd",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/mq-deadline.c:deadline_prio_aging_expire_show",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/thermal/gov_power_allocator.c:pid_controller",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/core/devlink.c:devlink_nl_health_reporter_fill",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756784,
      "name": "jiffies_to_msecs",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580839456,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:374",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/rcu/tree.c:print_cpu_stall_info",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:min_ttl_ms_show",
        "mm/mm_init.c:memmap_init_zone_device",
        "mm/mprotect.c:change_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/mq-deadline.c:deadline_prio_aging_expire_show",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/thermal/gov_power_allocator.c:pid_controller",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/devlink/health.c:devlink_nl_health_reporter_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580839456,
      "name": "jiffies_to_msecs",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928880,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:377",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_all_workqueues",
        "kernel/sched/core.c:sysctl_numa_balancing",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/fair.c:should_numa_migrate_memory",
        "kernel/sched/build_policy.c:sched_rr_handler",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/rcu/tree.c:print_cpu_stat_info",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:min_ttl_ms_show",
        "mm/mm_init.c:memmap_init_zone_device",
        "mm/mprotect.c:change_pte_range",
        "mm/huge_memory.c:change_huge_pmd",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show",
        "block/mq-deadline.c:deadline_prio_aging_expire_show",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/xen/events/events_base.c:handle_irq_for_port",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet",
        "drivers/scsi/scsi_ioctl.c:sg_io",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_proc_debug_helper",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl_common",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/power/supply/charger-manager.c:cm_setup_timer",
        "drivers/thermal/gov_power_allocator.c:pid_controller",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stat_for_entry",
        "drivers/mmc/core/sdio_cis.c:cistpl_funce_func",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/sched/sch_generic.c:dev_watchdog",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp.c:tcp_get_info",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/devlink/health.c:devlink_nl_health_reporter_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928880,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491309872,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/psci.c:cpu_psci_cpu_kill",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491309872,
      "name": "jiffies_to_msecs",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225306424,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/ata/libahci.c:ahci_do_softreset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_jiffies_to_msec64",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225306424,
      "name": "jiffies_to_msecs",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284235856,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index",
        "drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284235856,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271818868,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271818868,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068160,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068160,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012976,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012976,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580059232,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059232,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
unsigned int jiffies_to_msecs(const long unsigned int j)
```

```json
{
  "name": "jiffies_to_msecs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110064,
      "name": "jiffies_to_msecs",
      "external": true,
      "loc": "kernel/time/time.c:376",
      "file": "kernel/time/time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status",
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access",
        "kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv",
        "kernel/workqueue.c:show_workqueue_state",
        "kernel/irq/proc.c:irq_spurious_proc_show",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep_interruptible",
        "mm/page_alloc.c:memmap_init_zone_device",
        "fs/jbd2/transaction.c:do_get_write_access",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:jbd2_seq_info_show",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats",
        "block/blk-sysfs.c:queue_io_timeout_show",
        "block/genhd.c:diskstats_show",
        "block/genhd.c:diskstats_show",
        "block/partition-generic.c:part_stat_show",
        "block/partition-generic.c:part_stat_show",
        "block/scsi_ioctl.c:scsi_cmd_ioctl",
        "block/scsi_ioctl.c:sg_io",
        "block/mq-deadline.c:deadline_write_expire_show",
        "block/mq-deadline.c:deadline_read_expire_show",
        "drivers/pwm/sysfs.c:capture_show",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/tty/tty_port.c:tty_port_close_end",
        "drivers/tty/serial/serial_core.c:uart_wait_until_sent",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/tty/serial/serial_core.c:uart_get_info",
        "drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_error.c:scsi_send_eh_cmnd",
        "drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/scsi_debugfs.c:scsi_show_rq",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_add_request",
        "drivers/scsi/sg.c:sg_rq_end_io",
        "drivers/scsi/sg.c:sg_ioctl",
        "drivers/ata/libata-scsi.c:ata_scsi_park_show",
        "drivers/ata/libata-eh.c:ata_eh_reset",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:active_duration_show",
        "drivers/usb/core/sysfs.c:connected_duration_show",
        "drivers/power/supply/charger-manager.c:cm_suspend_complete",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/power/supply/charger-manager.c:cm_suspend_prepare",
        "drivers/md/md-bitmap.c:timeout_show",
        "drivers/md/dm-stats.c:dm_stats_account_io",
        "drivers/devfreq/devfreq.c:trans_stat_show",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/neighbour.c:neightbl_fill_parms",
        "net/core/net-sysfs.c:bql_show_hold_time",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_metrics.c:tcp_metrics_fill_info",
        "net/ipv4/tcp_cubic.c:bictcp_acked",
        "net/ipv4/tcp_cubic.c:bictcp_cong_avoid",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs",
        "net/ipv6/addrconf.c:inet6_fill_ifla6_attrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110064,
      "name": "jiffies_to_msecs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
