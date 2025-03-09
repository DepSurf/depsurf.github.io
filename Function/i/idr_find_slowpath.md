# Function: <code>idr_find_slowpath</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * idr_find_slowpath(struct idr * idp, int id)
```

```json
{
  "name": "idr_find_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582950992,
      "name": "idr_find_slowpath",
      "external": true,
      "loc": "lib/idr.c:642",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/cgroup.c:css_from_id",
        "kernel/events/core.c:perf_event_alloc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipc_get_maxid",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipcget",
        "ipc/namespace.c:free_ipcs",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950992,
      "name": "idr_find_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void * idr_find_slowpath(struct idr * idp, int id)
```

```json
{
  "name": "idr_find_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583238672,
      "name": "idr_find_slowpath",
      "external": true,
      "loc": "lib/idr.c:642",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/cgroup.c:css_from_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_get_maxid",
        "ipc/namespace.c:free_ipcs",
        "block/bsg.c:bsg_open",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238672,
      "name": "idr_find_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * idr_find_slowpath(struct idr * idp, int id)
```

```json
{
  "name": "idr_find_slowpath",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583353824,
      "name": "idr_find_slowpath",
      "external": true,
      "loc": "lib/idr.c:642",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/cgroup.c:css_from_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_get_maxid",
        "ipc/namespace.c:free_ipcs",
        "block/bsg.c:bsg_open",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353824,
      "name": "idr_find_slowpath",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void * idr_find_slowpath(struct idr * idp, int id)
```
</details>
</li>
</ul>
