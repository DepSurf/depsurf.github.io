# Function: <code>flush_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471296,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2481",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_post_attach_flush",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/mmc/core/core.c:mmc_stop_host"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471296,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1485
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579485088,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2577",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/base/dd.c:wait_for_device_probe",
        "drivers/base/dd.c:deferred_probe_initcall",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579485088,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1376
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505888,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2579",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505888,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1404
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494576,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2578",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_event",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494576,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 997
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579521312,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2596",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_put_super",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_event",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579521312,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 953
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546496,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2643",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_event",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546496,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579583488,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2666",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_event",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579583488,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 993
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2762",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_event",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627354,
      "name": "flush_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579606992,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1047
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579632720,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632720,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579663328,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2768",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579663328,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1022
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643136,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2774",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643136,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1022
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579650832,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2775",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650832,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1046
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2814",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/osl.c:acpi_hotplug_work_fn",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/io-pgfault.c:iopf_queue_flush_dev",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592104260,
      "name": "flush_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579727696,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 976
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490798640,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/eventfd.c:kvm_irqfd_release",
        "virt/kvm/eventfd.c:kvm_irqfd",
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490798640,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1080
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224841832,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224841832,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1508
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283634240,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283634240,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1268
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271479972,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271479972,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 706
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579609024,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/nvme/host/pci.c:nvme_exit",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609024,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537664,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/nfit/core.c:__acpi_nfit_notify",
        "drivers/acpi/nfit/core.c:acpi_nfit_shutdown",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_rolechg",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_add",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_add",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_add",
        "drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete",
        "drivers/scsi/scsi_transport_fc.c:fc_rport_final_delete",
        "drivers/nvme/host/pci.c:nvme_exit",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537664,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579606304,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606304,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
void flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579643168,
      "name": "flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2771",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:drain_workqueue",
        "kernel/cgroup/cgroup-v1.c:cgroup1_pidlist_destroy_all",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_post_attach",
        "mm/slab_common.c:kmem_cache_destroy",
        "fs/fs-writeback.c:cgroup_writeback_umount",
        "fs/io_uring.c:io_destruct_skb",
        "fs/io_uring.c:io_destruct_skb",
        "fs/ext4/super.c:ext4_sync_fs",
        "block/bio-integrity.c:blk_flush_integrity",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_release",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm.c:local_exit",
        "drivers/edac/wq.c:edac_workqueue_teardown",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643168,
      "name": "flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1054
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void flush_workqueue(struct workqueue_struct * wq)
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
