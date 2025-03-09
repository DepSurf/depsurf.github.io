# Function: <code>__flush_workqueue</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void __flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "__flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2797",
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
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/io-pgfault.c:iopf_queue_flush_dev",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/vfio/virqfd.c:vfio_virqfd_disable",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_open",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:flush_rdev_wq",
        "drivers/md/dm.c:dm_internal_suspend_fast",
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
      "addr": 18446744071593872022,
      "name": "__flush_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579836288,
      "name": "__flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void __flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "__flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:2797",
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
        "drivers/pci/doe.c:pci_doe_flush_mb",
        "drivers/rapidio/rio.c:rio_init_mports",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/io-pgfault.c:iopf_queue_flush_dev",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/md.c:flush_rdev_wq",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595976120,
      "name": "__flush_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579970992,
      "name": "__flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 977
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void __flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "__flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:3113",
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
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_remove_query_handler",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/iommu/io-pgfault.c:iopf_queue_flush_dev",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:__md_stop",
        "drivers/md/md.c:__md_stop_writes",
        "drivers/md/md.c:md_alloc",
        "drivers/md/md.c:action_store",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596493535,
      "name": "__flush_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580021056,
      "name": "__flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 990
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __flush_workqueue(struct workqueue_struct * wq)
```

```json
{
  "name": "__flush_workqueue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__flush_workqueue",
      "external": true,
      "loc": "kernel/workqueue.c:3134",
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
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/osl.c:acpi_os_wait_events_complete",
        "drivers/acpi/ec.c:acpi_ec_remove_query_handler",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/ec.c:__acpi_ec_flush_work",
        "drivers/acpi/thermal.c:acpi_thermal_suspend",
        "drivers/acpi/thermal.c:acpi_thermal_remove",
        "drivers/acpi/thermal.c:acpi_thermal_add",
        "drivers/iommu/io-pgfault.c:iopf_queue_flush_dev",
        "drivers/scsi/hosts.c:scsi_flush_work",
        "drivers/scsi/hosts.c:scsi_remove_host",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_free",
        "drivers/md/md.c:md_alloc",
        "drivers/md/dm.c:dm_internal_suspend_fast",
        "drivers/md/dm.c:__dm_suspend",
        "drivers/md/dm-kcopyd.c:dm_kcopyd_client_flush",
        "drivers/edac/wq.c:edac_stop_work",
        "net/sched/cls_api.c:unregister_tcf_proto_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597390379,
      "name": "__flush_workqueue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580062704,
      "name": "__flush_workqueue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 990
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __flush_workqueue(struct workqueue_struct * wq)
```
</details>
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
