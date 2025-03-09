# Function: <code>kthread_create_on_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501168,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:270",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "fs/notify/mark.c:fsnotify_mark_init",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/virtio/virtio_balloon.c:virtballoon_probe",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/md/md.c:md_register_thread",
        "drivers/md/dm.c:init_rq_based_worker_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501168,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515232,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:270",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_receive_msg",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "mm/oom_kill.c:oom_init",
        "mm/compaction.c:kcompactd_run",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/md/md.c:md_register_thread",
        "drivers/md/dm-rq.c:dm_old_init_request_queue",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515232,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 479
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579536400,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:357",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "mm/oom_kill.c:oom_init",
        "mm/compaction.c:kcompactd_run",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_master",
        "drivers/md/md.c:md_register_thread",
        "drivers/md/dm-rq.c:dm_old_init_request_queue",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579536400,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523568,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:361",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "mm/oom_kill.c:oom_init",
        "mm/compaction.c:kcompactd_run",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/md/md.c:md_register_thread",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523568,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579549952,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:368",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:__alloc_workqueue_key",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/compaction.c:kcompactd_run",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/md/md.c:md_register_thread",
        "drivers/md/dm-rq.c:dm_old_init_request_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579549952,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579280,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:382",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/md/md.c:md_register_thread",
        "drivers/md/dm-rq.c:dm_old_init_request_queue",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579280,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579616464,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:382",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:lo_ioctl",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579616464,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638896,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638896,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664832,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664832,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579700672,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:427",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_sq_offload_start",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_test",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_start_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_init",
        "drivers/char/hw_random/core.c:hwrng_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_init_queue",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579700672,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579678832,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:429",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace_hwlat.c:start_kthread",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_sq_offload_create",
        "fs/io-wq.c:io_wq_create",
        "fs/io-wq.c:create_io_worker",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_test",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_start_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_init",
        "drivers/char/hw_random/core.c:hwrng_init",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579678832,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579685104,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:456",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_test",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_configure",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "net/core/dev.c:napi_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579685104,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579763392,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:456",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_test",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "net/core/dev.c:napi_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579763392,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579868960,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:init_rescuer",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_test",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "net/core/dev.c:napi_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579868960,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580011648,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:init_rescuer",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "net/core/dev.c:napi_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011648,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580065184,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:516",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:init_rescuer",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "net/core/dev.c:napi_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065184,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580107792,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:515",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_cycles",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:init_rescuer",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/build_utility.c:psi_trigger_create",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread_generic",
        "kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread",
        "kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:__cpu_map_entry_alloc",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/jbd2/journal.c:journal_reset",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_schedule_probe",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/balloon.c:balloon_init",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_initcall",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq",
        "net/core/dev.c:napi_kthread_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580107792,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490843528,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vm_create_worker_thread",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490843528,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224875280,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_start",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224875280,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283677712,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh_event.c:eeh_event_init",
        "arch/powerpc/platforms/powernv/opal.c:opal_init",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283677712,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271513464,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271513464,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641152,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641152,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579569552,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_one_nocb_kthread",
        "kernel/rcu/tree.c:rcu_spawn_one_nocb_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579569552,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579638416,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638416,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
struct task_struct * kthread_create_on_node(int (*)(void *) threadfn, void * data, int node, const char * namefmt, void (anon))
```

```json
{
  "name": "kthread_create_on_node",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579672256,
      "name": "kthread_create_on_node",
      "external": true,
      "loc": "kernel/kthread.c:391",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_measure_trigger",
        "kernel/workqueue.c:create_worker",
        "kernel/kthread.c:kthread_create_on_cpu",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/irq/manage.c:setup_irq_thread",
        "kernel/rcu/update.c:rcu_spawn_tasks_kthread",
        "kernel/rcu/tree.c:rcu_spawn_gp_kthread",
        "kernel/time/clocksource.c:clocksource_watchdog_work",
        "kernel/audit.c:audit_init",
        "kernel/auditfilter.c:audit_list_rules_send",
        "kernel/audit_tree.c:audit_add_tree_rule",
        "kernel/hung_task.c:hung_task_init",
        "kernel/bpf/cpumap.c:cpu_map_update_elem",
        "mm/oom_kill.c:oom_init",
        "mm/vmscan.c:kswapd_run",
        "mm/compaction.c:kcompactd_run",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/ext4/mmp.c:ext4_multi_mount_protect",
        "fs/ext4/super.c:ext4_register_li_request",
        "fs/ecryptfs/kthread.c:ecryptfs_init_kthread",
        "security/tomoyo/gc.c:tomoyo_notify_gc",
        "crypto/algboss.c:cryptomgr_notify",
        "crypto/algboss.c:cryptomgr_notify",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init_notification",
        "drivers/acpi/acpi_dbg.c:acpi_aml_create_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xb_init_comms",
        "drivers/xen/xenbus/xenbus_xs.c:xs_init",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/base/devtmpfs.c:devtmpfs_init",
        "drivers/block/loop.c:loop_set_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/usb/early/ehci-dbgp.c:kgdbdbgp_start_thread",
        "drivers/usb/early/xhci-dbc.c:xdbc_init",
        "drivers/media/cec/cec-core.c:cec_allocate_adapter",
        "drivers/media/cec/cec-adap.c:cec_claim_log_addrs",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/md/md.c:md_register_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_claim_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672256,
      "name": "kthread_create_on_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
