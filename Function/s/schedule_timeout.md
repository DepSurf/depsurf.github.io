# Function: <code>schedule_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587378016,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1493",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__usermodehelper_disable",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/locking/semaphore.c:__down",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/rcu/tree.c:synchronize_sched_expedited",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/time/timer.c:msleep",
        "kernel/module.c:load_module",
        "kernel/audit.c:audit_log_start",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:kswapd",
        "mm/huge_memory.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:SYSC_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/xenbus/xenbus_xs.c:read_reply",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_sendbyte",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_recv_datagram",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/unix/af_unix.c:unix_wait_for_peer",
        "net/unix/af_unix.c:unix_stream_read_generic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378016,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 621
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587880416,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1709",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:__usermodehelper_disable",
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:bit_wait_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "kernel/audit.c:audit_log_start",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:SYSC_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/xenbus/xenbus_xs.c:read_reply",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_sendbyte",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sk_wait_data",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/core/stream.c:sk_stream_wait_memory",
        "net/core/stream.c:sk_stream_wait_connect",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/ipv4/af_inet.c:__inet_stream_connect",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587880416,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1086
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097168,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1714",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kmod.c:__usermodehelper_disable",
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:bit_wait_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:SYSC_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/xenbus/xenbus_xs.c:read_reply",
        "drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_wait_for_backend",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/base/firmware_class.c:__fw_state_wait_common",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_sendbyte",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097168,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1004
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588322976,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1705",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write",
        "kernel/kmod.c:__usermodehelper_disable",
        "kernel/kmod.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:SYSC_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_sendbyte",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588322976,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 846
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588889056,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1754",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_sendbyte",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588889056,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 834
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589267296,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1765",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589267296,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589509856,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1764",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:rcu_exp_wait_wake",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589509856,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 861
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589969168,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1768",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589969168,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590196832,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590196832,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591212912,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1877",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:resolve_symbol_wait",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wqe_worker",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_wait_for_wmem",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212912,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591708176,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1839",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:resolve_symbol_wait",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wqe_worker",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_wait_for_wmem",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_wait_for_connect",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591708176,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591655552,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/locking/semaphore.c:__down_common",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:simplify_symbols",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/io_uring.c:io_cqring_wait",
        "fs/io-wq.c:io_wqe_worker",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591655552,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592829248,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1842",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/locking/semaphore.c:__down_common",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:simplify_symbols",
        "kernel/audit.c:audit_receive",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/io-wq.c:io_wqe_worker",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:__do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592829248,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594737984,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1896",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/build_utility.c:wait_woken",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/locking/semaphore.c:__down_common",
        "kernel/rcu/update.c:rcu_tasks_trace_postgp",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/module/main.c:simplify_symbols",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/locks.c:__break_lease",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "io_uring/io-wq.c:io_wqe_worker",
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/random.c:wait_for_random_bytes",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594737984,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596490032,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:2128",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/build_utility.c:wait_woken",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_killable_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_state",
        "kernel/sched/build_utility.c:wait_for_completion_killable",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible",
        "kernel/sched/build_utility.c:wait_for_completion_timeout",
        "kernel/sched/build_utility.c:wait_for_completion",
        "kernel/locking/semaphore.c:___down_common",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/module/main.c:simplify_symbols",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/locks.c:__break_lease",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "io_uring/io-wq.c:io_wqe_worker",
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/random.c:wait_for_random_bytes",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596490032,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597031344,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:2128",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/build_utility.c:wait_woken",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_killable_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_state",
        "kernel/sched/build_utility.c:wait_for_completion_killable",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible",
        "kernel/sched/build_utility.c:wait_for_completion_timeout",
        "kernel/sched/build_utility.c:wait_for_completion",
        "kernel/locking/semaphore.c:___down_common",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/module/main.c:simplify_symbols",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/locks.c:__break_lease",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "io_uring/io-wq.c:io_wq_worker",
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/random.c:wait_for_random_bytes",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597031344,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597960736,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:2144",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/build_utility.c:wait_woken",
        "kernel/sched/build_utility.c:bit_wait_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_killable_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_state",
        "kernel/sched/build_utility.c:wait_for_completion_killable",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/build_utility.c:wait_for_completion_interruptible",
        "kernel/sched/build_utility.c:wait_for_completion_timeout",
        "kernel/sched/build_utility.c:wait_for_completion",
        "kernel/locking/semaphore.c:___down_common",
        "kernel/rcu/tree.c:synchronize_rcu_expedited_wait_once",
        "kernel/rcu/tree.c:rcu_gp_fqs_loop",
        "kernel/module/main.c:simplify_symbols",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/audit.c:audit_log_start",
        "kernel/audit.c:audit_receive",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/vmscan.c:reclaim_throttle",
        "mm/compaction.c:kcompactd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/locks.c:__break_lease",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "io_uring/io-wq.c:io_wq_worker",
        "drivers/pci/pcie/dpc.c:pci_dpc_recovered",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/char/random.c:wait_for_random_bytes",
        "drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find_fence",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_vblank_ioctl",
        "drivers/gpu/drm/drm_vblank.c:drm_wait_one_vblank",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_bus_close",
        "drivers/net/xen-netfront.c:xennet_create_dev",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_data_wait",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597960736,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503943968,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503943968,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 396
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236552468,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:try_to_free_pages",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/misc/vexpress-syscfg.c:vexpress_syscfg_exec",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_trx_complete",
        "drivers/i2c/busses/i2c-s3c2410.c:s3c24xx_i2c_xfer",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_ioctl",
        "drivers/pps/pps.c:pps_cdev_ioctl",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/host/sdhci.c:sdhci_send_tuning",
        "drivers/mmc/host/cqhci.c:cqhci_halt",
        "sound/core/pcm_native.c:snd_pcm_drain",
        "sound/core/pcm_lib.c:__snd_pcm_lib_xfer",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236552468,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 812
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297796336,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/opal.c:kopald",
        "arch/powerpc/platforms/powernv/vas-window.c:vas_win_close",
        "arch/powerpc/platforms/powernv/vas-window.c:vas_win_close",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/hvc/hvsi.c:hvsi_close",
        "drivers/tty/hvc/hvsi.c:wait_for_state",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/char/tpm/tpm_i2c_nuvoton.c:i2c_nuvoton_wait_for_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297796336,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279807592,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279807592,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589799120,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589799120,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589521568,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589521568,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590242528,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590242528,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
long int schedule_timeout(long int timeout)
```

```json
{
  "name": "schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590292832,
      "name": "schedule_timeout",
      "external": true,
      "loc": "kernel/time/timer.c:1856",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_pv.c:xen_pv_cpu_die",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_chrdev_write",
        "kernel/umh.c:__usermodehelper_disable",
        "kernel/umh.c:usermodehelper_read_lock_wait",
        "kernel/kmod.c:__request_module",
        "kernel/sched/core.c:io_schedule_timeout",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/wait_bit.c:bit_wait_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable_timeout",
        "kernel/sched/completion.c:wait_for_completion_killable",
        "kernel/sched/completion.c:wait_for_completion_interruptible_timeout",
        "kernel/sched/completion.c:wait_for_completion_interruptible",
        "kernel/sched/completion.c:wait_for_completion_timeout",
        "kernel/sched/completion.c:wait_for_completion",
        "kernel/locking/semaphore.c:__down_timeout",
        "kernel/locking/semaphore.c:__down_killable",
        "kernel/locking/semaphore.c:__down_interruptible",
        "kernel/locking/semaphore.c:__down",
        "kernel/rcu/tree.c:synchronize_sched_expedited_wait",
        "kernel/rcu/tree.c:rcu_gp_kthread",
        "kernel/time/timer.c:msleep_interruptible",
        "kernel/time/timer.c:msleep",
        "kernel/time/timer.c:schedule_timeout_idle",
        "kernel/time/timer.c:schedule_timeout_killable",
        "kernel/module.c:load_module",
        "mm/oom_kill.c:oom_killer_disable",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "fs/locks.c:__break_lease",
        "ipc/sem.c:do_semtimedop",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "block/blk-mq.c:blk_mq_freeze_queue_wait_timeout",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_write_cmd",
        "drivers/acpi/ec.c:ec_guard",
        "drivers/tty/tty_ioctl.c:tty_wait_until_sent",
        "drivers/tty/tty_ldsem.c:ldsem_down_write",
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/char/tpm/tpm_tis_core.c:request_locality",
        "drivers/char/tpm/tpm_tis_core.c:release_locality",
        "drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat",
        "drivers/dma-buf/dma-fence.c:dma_fence_wait_any_timeout",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/dma-buf/dma-fence.c:dma_fence_default_wait",
        "drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:__ps2_command",
        "drivers/input/serio/libps2.c:ps2_drain",
        "drivers/input/serio/libps2.c:ps2_do_sendbyte",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-api.c:cec_receive_msg",
        "drivers/pps/pps.c:pps_cdev_pps_fetch",
        "drivers/md/md.c:md_wait_for_blocked_rdev",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_ioctl",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/sock.c:sock_alloc_send_pskb",
        "net/core/datagram.c:__skb_wait_for_more_packets",
        "net/netlink/af_netlink.c:netlink_attachskb",
        "net/ipv4/inet_connection_sock.c:inet_csk_accept",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_stream_read_generic",
        "net/unix/af_unix.c:unix_wait_for_peer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590292832,
      "name": "schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 767
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
