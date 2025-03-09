# Function: <code>idr_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_find",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579466398,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_work_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579998701,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580413017,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581278356,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582140391,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipc_get_maxid",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipcget"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165668,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582182105,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:free_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582821220,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582868893,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584331858,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:prq_event_thread"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584544577,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584887743,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585105021,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585640500,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_get_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585808686,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_md"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586253688,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_find",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579480442,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_work_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580030677,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485429,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091404,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581444180,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582356439,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_get_maxid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582381908,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582398361,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:free_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100468,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583154125,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584679641,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584895073,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585250271,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489105,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586040504,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_get_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586202313,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_md"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586677928,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:115",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_find",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500378,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_work_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064853,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580546562,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166620,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581524996,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582447815,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_get_maxid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582474068,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582490537,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:free_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583211988,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583265037,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584764140,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584866153,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085329,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585450031,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585676715,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586238008,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/i2c/i2c-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core.c:i2c_get_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586406809,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_md"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586862291,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587150484,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:140",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_find",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579489099,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_work_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580060217,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580493434,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574291,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581214435,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577968,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582528825,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipcget",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_get_maxid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582554816,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582571426,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:free_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270039,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583319245,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584846279,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584953897,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585167441,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585533835,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585764261,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586314280,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586510400,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_md"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586985795,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587281424,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:131",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_find",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579515531,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:get_work_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579541024,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580110985,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_from_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549996,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580655177,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581345059,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722375,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581987481,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582677070,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_rmid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582706823,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "ipc/shm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582724114,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "ipc/namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/namespace.c:free_ipcs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583448060,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/genhd.c:get_gendisk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583503341,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266951,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_find_get"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375012,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594737,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585964267,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137605,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_unregister_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586210202,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586776968,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586977888,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_get_md"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587484131,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:get_net_ns_by_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801504,
      "name": "idr_find",
      "external": false,
      "loc": "include/linux/idr.h:193",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130080,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:175",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_get_fd_by_id",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_lock",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-svm.c:prq_event_thread",
        "drivers/iommu/intel-svm.c:intel_svm_is_pasid_valid",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tc_dump_tfilter",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_check",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130080,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364736,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:171",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364736,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821760,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821760,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048048,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048048,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042016,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_link_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_init_event",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_charge",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_provide_buffers",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_connect_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "drivers/interconnect/core.c:icc_get",
        "drivers/interconnect/core.c:icc_get",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_delete_index",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042016,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193744,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_init_event",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_charge",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_remove_buffers",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_connect_channel",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "drivers/interconnect/core.c:icc_get",
        "drivers/interconnect/core.c:icc_get",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_delete_index",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193744,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076832,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_init_event",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipcctl_obtain_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "drivers/interconnect/core.c:icc_get",
        "drivers/interconnect/core.c:icc_get",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_action_delete",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076832,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523664,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_init_event",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/namespace.c:free_ipcs",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "drivers/interconnect/core.c:icc_get",
        "drivers/interconnect/core.c:icc_get",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523664,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676736,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:sysvipc_find_ipc",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/namespace.c:free_ipcs",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_install",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "drivers/interconnect/core.c:icc_get",
        "drivers/interconnect/core.c:icc_get",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676736,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595756864,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/namespace.c:free_ipcs",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_install",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "drivers/interconnect/core.c:icc_get",
        "drivers/interconnect/core.c:icc_get",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595756864,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596281184,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:__queue_work",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_init_event",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/namespace.c:free_ipcs",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_install",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596281184,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597165888,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:work_busy",
        "kernel/workqueue.c:try_to_grab_pending",
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "kernel/pid.c:find_get_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_init_event",
        "mm/shrinker.c:shrink_slab_memcg",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_id",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/shm.c:shmctl_shm_info",
        "ipc/namespace.c:free_ipcs",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/gpu/drm/drm_auth.c:drm_authmagic",
        "drivers/gpu/drm/drm_drv.c:drm_minor_acquire",
        "drivers/gpu/drm/drm_gem.c:drm_gem_open_ioctl",
        "drivers/gpu/drm/drm_gem.c:objects_lookup",
        "drivers/gpu/drm/drm_lease.c:drm_mode_revoke_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_lease.c:drm_lease_filter_crtcs",
        "drivers/gpu/drm/drm_lease.c:drm_lease_held",
        "drivers/gpu/drm/drm_lease.c:_drm_lease_held",
        "drivers/gpu/drm/drm_mode_object.c:__drm_mode_object_find",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_find",
        "drivers/accel/drm_accel.c:accel_minor_acquire",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_install",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_link_create",
        "drivers/interconnect/core.c:icc_node_destroy",
        "drivers/interconnect/core.c:icc_node_create",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_dumppolicy_start",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597165888,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503822712,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/firmware/arm_scmi/bus.c:scmi_dev_probe",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup",
        "drivers/firmware/arm_scmi/driver.c:scmi_do_xfer",
        "drivers/of/overlay.c:of_overlay_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503822712,
      "name": "idr_find",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236444212,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/pid.c:find_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/shm.c:ksys_shmctl",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/mtd/mtdcore.c:get_mtd_device",
        "drivers/mtd/mtdcore.c:del_mtd_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/firmware/arm_scmi/bus.c:scmi_dev_probe",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup",
        "drivers/firmware/arm_scmi/driver.c:scmi_do_xfer",
        "drivers/of/overlay.c:of_overlay_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236444212,
      "name": "idr_find",
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297667520,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/notify/inotify/inotify_user.c:inotify_idr_find_locked",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/of/overlay.c:of_overlay_remove",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297667520,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279718120,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/of/overlay.c:of_overlay_remove",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279718120,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650304,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650304,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376112,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376112,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093680,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093680,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
void * idr_find(const struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_find",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590143936,
      "name": "idr_find",
      "external": true,
      "loc": "lib/idr.c:172",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_work_pool",
        "kernel/pid.c:find_get_pid",
        "kernel/pid.c:find_task_by_vpid",
        "kernel/cgroup/cgroup.c:css_from_id",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/btf.c:btf_get_fd_by_id",
        "kernel/events/core.c:perf_event_alloc",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino",
        "ipc/util.c:ipc_obtain_object_check",
        "ipc/util.c:ipc_rmid",
        "ipc/namespace.c:free_ipcs",
        "block/genhd.c:get_gendisk",
        "block/bsg.c:bsg_open",
        "drivers/iommu/intel-pasid.c:intel_pasid_lookup_id",
        "drivers/scsi/sg.c:sg_proc_seq_show_debug",
        "drivers/scsi/sg.c:sg_proc_seq_show_devstrs",
        "drivers/scsi/sg.c:sg_proc_seq_show_dev",
        "drivers/scsi/sg.c:sg_open",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/vfio/vfio.c:vfio_group_fops_open",
        "drivers/i2c/i2c-core-base.c:i2c_get_adapter",
        "drivers/md/dm.c:dm_get_md",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_vq_interrupt",
        "net/core/net_namespace.c:get_net_ns_by_id",
        "net/sched/cls_api.c:tcf_block_refcnt_get",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_check_alloc",
        "net/sched/act_api.c:tcf_idr_search",
        "net/netlink/genetlink.c:ctrl_getfamily",
        "net/netlink/genetlink.c:genl_rcv_msg",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143936,
      "name": "idr_find",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * idr_find(const struct idr * idr, long unsigned int id)
```
</details>
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
