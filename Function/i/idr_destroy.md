# Function: <code>idr_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void idr_destroy(struct idr * idp)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949952,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/idr.c:631",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:cgroup_free_root",
        "mm/shmem.c:shmem_put_super",
        "mm/shmem.c:shmem_init",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "lib/idr.c:ida_destroy",
        "drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949952,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void idr_destroy(struct idr * idp)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237616,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/idr.c:631",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "lib/idr.c:ida_destroy",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237616,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
void idr_destroy(struct idr * idp)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352768,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/idr.c:631",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_mount",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "lib/idr.c:ida_destroy",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_exit",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352768,
      "name": "idr_destroy",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588220800,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:2223",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588220800,
      "name": "idr_destroy",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588770768,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:2220",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770768,
      "name": "idr_destroy",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589149536,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:2221",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/iommu/intel-svm.c:intel_svm_free_pasid_tables",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589149536,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589383648,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1581",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589383648,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 211
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589840720,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589840720,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590066816,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590066816,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585061824,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1560",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_fill_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:unhash_nsid",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585061824,
      "name": "idr_destroy",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585211120,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1560",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:unhash_nsid",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211120,
      "name": "idr_destroy",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585093968,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1561",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585093968,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585541552,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1561",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541552,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586696992,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1561",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586696992,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595857872,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1561",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595857872,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596374768,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1559",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596374768,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597270016,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1559",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:create_pid_namespace",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/gpu/drm/drm_auth.c:drm_master_destroy",
        "drivers/gpu/drm/drm_auth.c:drm_master_destroy",
        "drivers/gpu/drm/drm_auth.c:drm_master_destroy",
        "drivers/gpu/drm/drm_drv.c:drm_core_init",
        "drivers/gpu/drm/drm_gem.c:drm_gem_release",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_mode_config.c:drm_mode_config_cleanup",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_release",
        "drivers/accel/drm_accel.c:accel_core_exit",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_exit",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597270016,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503842616,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503842616,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236461844,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/mtd/mtdcore.c:cleanup_mtd",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "drivers/firmware/arm_scmi/driver.c:scmi_remove",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236461844,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297695056,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:put_pid_ns",
        "kernel/pid_namespace.c:copy_pid_ns",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297695056,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279734680,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279734680,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589669072,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589669072,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589394896,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589394896,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590112448,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590112448,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void idr_destroy(struct idr * idr)
```

```json
{
  "name": "idr_destroy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162816,
      "name": "idr_destroy",
      "external": true,
      "loc": "lib/radix-tree.c:1568",
      "file": "lib/radix-tree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/pid_namespace.c:copy_pid_ns",
        "kernel/pid_namespace.c:destroy_pid_namespace",
        "mm/shmem.c:shmem_init",
        "mm/shmem.c:shmem_put_super",
        "fs/notify/inotify/inotify_fsnotify.c:inotify_free_group_priv",
        "fs/kernfs/dir.c:kernfs_create_root",
        "ipc/msg.c:msg_exit_ns",
        "ipc/sem.c:sem_exit_ns",
        "ipc/shm.c:shm_exit_ns",
        "drivers/char/tpm/tpm-interface.c:tpm_exit",
        "drivers/block/loop.c:loop_exit",
        "drivers/scsi/sg.c:exit_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_exit_net",
        "drivers/vfio/vfio.c:vfio_cleanup",
        "drivers/usb/core/usb.c:usb_exit",
        "drivers/md/dm.c:dm_exit",
        "drivers/remoteproc/remoteproc_core.c:rproc_type_release",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_net_exit",
        "net/sched/act_api.c:tcf_idrinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162816,
      "name": "idr_destroy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct idr * idr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct idr * idp</code>
</li>
</ul>
</details>
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
