# Function: <code>kthread_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579502576,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:491",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "mm/vmscan.c:kswapd_stop",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/virtio/virtio_balloon.c:virtballoon_remove",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579502576,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516640,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:491",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516640,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538736,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:519",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538736,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525664,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:523",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525664,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551664,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:530",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551664,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579580336,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:548",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/md/dm.c:cleanup_mapped_device",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579580336,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579617968,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:550",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617968,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_uring_create",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644758,
      "name": "kthread_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579642528,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667984,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579667984,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579699744,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:595",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_sq_offload_start",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_init",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/md/md.c:md_unregister_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579699744,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579677344,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:621",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_sq_thread_stop",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_init",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:hwrng_init",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677344,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579684048,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:648",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/sched/psi.c:psi_trigger_destroy",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_stop_mmpd",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684048,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 351
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579762192,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:648",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_hwlat.c:hwlat_cpu_die",
        "kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_stop_mmpd",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579762192,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871504,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:708",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_hwlat.c:hwlat_cpu_die",
        "kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_stop_mmpd",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871504,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014432,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:708",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_hwlat.c:hwlat_cpu_die",
        "kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_stop_mmpd",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014432,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580068176,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:709",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_hwlat.c:hwlat_cpu_die",
        "kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads",
        "kernel/trace/trace_osnoise.c:stop_kthread",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_stop_mmpd",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580068176,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580110816,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:708",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_init",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/kthread.c:kthread_stop_put",
        "kernel/sched/build_utility.c:psi_trigger_destroy",
        "kernel/sched/build_utility.c:sugov_exit",
        "kernel/sched/build_utility.c:sugov_init",
        "kernel/sched/build_utility.c:sugov_kthread_create",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_mode_write",
        "kernel/trace/trace_hwlat.c:hwlat_cpu_die",
        "kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads",
        "kernel/trace/trace_osnoise.c:stop_kthread",
        "kernel/bpf/cpumap.c:__cpu_map_entry_free",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/ext4/mmp.c:ext4_stop_mmpd",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580110816,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490845480,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490845480,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224873548,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_active_store",
        "arch/arm/common/bL_switcher.c:bL_switcher_active_store",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/smpboot.c:smpboot_destroy_threads",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224873548,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283683696,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/char/hw_random/core.c:set_current_rng",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283683696,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271512396,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271512396,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644304,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644304,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572688,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572688,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641568,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579641568,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int kthread_stop(struct task_struct * k)
```

```json
{
  "name": "kthread_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579675808,
      "name": "kthread_stop",
      "external": true,
      "loc": "kernel/kthread.c:559",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/kthread.c:kthread_destroy_worker",
        "kernel/sched/cpufreq_schedutil.c:sugov_exit",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/sched/cpufreq_schedutil.c:sugov_init",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:load_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/power/swap.c:save_image_lzo",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__free_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/irq/manage.c:__setup_irq",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_reset",
        "kernel/trace/trace_hwlat.c:hwlat_tracer_stop",
        "kernel/bpf/cpumap.c:cpu_map_kthread_stop",
        "mm/vmscan.c:kswapd_stop",
        "mm/compaction.c:kcompactd_stop",
        "mm/ksm.c:ksm_init",
        "mm/khugepaged.c:start_stop_khugepaged",
        "fs/io_uring.c:io_finish_async",
        "fs/ext4/super.c:ext4_exit_fs",
        "fs/ext4/super.c:ext4_remount",
        "fs/ext4/super.c:ext4_fill_super",
        "fs/ext4/super.c:ext4_put_super",
        "fs/ecryptfs/kthread.c:ecryptfs_destroy_kthread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_stop",
        "drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_unregister_controller",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_shutdown_notification",
        "drivers/tty/hvc/hvc_console.c:hvc_alloc",
        "drivers/char/hw_random/core.c:hwrng_unregister",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/scsi/hosts.c:scsi_host_alloc",
        "drivers/scsi/hosts.c:scsi_host_dev_release",
        "drivers/spi/spi.c:spi_destroy_queue",
        "drivers/media/cec/cec-pin.c:cec_pin_adap_enable",
        "drivers/md/md.c:md_unregister_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_release_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675808,
      "name": "kthread_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
