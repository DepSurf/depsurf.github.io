# Function: <code>kthread_should_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579500640,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:79",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/kthread.c:kthread_worker_fn"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/virtio/virtio_balloon.c:balloon",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500640,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579517300,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:79",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514704,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579535376,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:88",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535376,
      "name": "kthread_should_stop",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579522656,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:91",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579522656,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579548976,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:99",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548976,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579581160,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:98",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579904,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579617272,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:98",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579617584,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579641611,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644701,
      "name": "kthread_should_stop.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579642048,
      "name": "kthread_should_stop",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579668665,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663920,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579702491,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:108",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_wait_for_interrupt",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_do_scan",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698944,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579680413,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:109",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_wait_for_interrupt",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_do_scan",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io_uring.c:io_sq_thread",
        "fs/io-wq.c:io_wq_manager",
        "fs/io-wq.c:io_wq_manager",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579677024,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579686893,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:134",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579683472,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579765192,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:134",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/sched/psi.c:psi_poll_worker",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760112,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579872084,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:155",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/vfio/vfio_iommu_type1.c:vfio_wait",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579866672,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015036,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:155",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:psi_poll_worker",
        "kernel/sched/build_utility.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009104,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580068780,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:156",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:osnoise_main",
        "kernel/trace/trace_osnoise.c:osnoise_sleep",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062944,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580111564,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:156",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/sched/build_utility.c:psi_rtpoll_worker",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/trace/trace_osnoise.c:timerlat_main",
        "kernel/trace/trace_osnoise.c:osnoise_main",
        "kernel/trace/trace_osnoise.c:osnoise_sleep",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:kswapd_try_to_sleep",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "mm/khugepaged.c:khugepaged_wait_work",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:poll_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "net/core/dev.c:napi_threaded_poll",
        "net/core/dev.c:napi_threaded_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580105568,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490840248,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:kvm_vm_worker_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/irq/manage.c:irq_thread",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490840248,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224869448,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/common/bL_switcher.c:bL_switcher_thread",
        "arch/arm/common/bL_switcher.c:bL_switcher_thread",
        "arch/arm/common/bL_switcher.c:bL_switcher_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224869448,
      "name": "kthread_should_stop",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283682580,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh_event.c:eeh_event_handler",
        "arch/powerpc/kernel/eeh_event.c:eeh_event_handler",
        "arch/powerpc/platforms/powernv/opal.c:kopald",
        "arch/powerpc/platforms/powernv/opal.c:kopald",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283683120,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271509782,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271509782,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579644985,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579640240,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579573369,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568640,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579642249,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637504,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool kthread_should_stop()
```

```json
{
  "name": "kthread_should_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579673118,
      "name": "kthread_should_stop",
      "external": true,
      "loc": "kernel/kthread.c:101",
      "file": "kernel/kthread.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_worker_fn",
        "kernel/kthread.c:kthread_freezable_should_stop"
      ],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/smpboot.c:smpboot_thread_fn",
        "kernel/sched/wait.c:wait_woken",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_decompress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:lzo_compress_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/power/swap.c:crc32_threadfn",
        "kernel/irq/manage.c:irq_thread",
        "kernel/freezer.c:__refrigerator",
        "kernel/audit.c:kauditd_thread",
        "kernel/trace/trace_hwlat.c:kthread_fn",
        "kernel/bpf/cpumap.c:cpu_map_kthread_run",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd",
        "mm/compaction.c:kcompactd_do_work",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/ksm.c:ksm_scan_thread",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "fs/ext4/mmp.c:kmmpd",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "fs/ecryptfs/kthread.c:ecryptfs_threadfn",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/cpci_hotplug_core.c:event_thread",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread",
        "drivers/xen/xenbus/xenbus_xs.c:xenwatch_thread",
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/random.c:add_hwgenerator_randomness",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/char/hw_random/core.c:hwrng_fillfn",
        "drivers/scsi/scsi_error.c:scsi_error_handler",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-adap.c:cec_thread_func",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/md/md.c:md_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread",
        "drivers/mmc/core/sdio_irq.c:sdio_irq_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671344,
      "name": "kthread_should_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
