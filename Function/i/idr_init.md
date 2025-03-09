# Function: <code>idr_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void idr_init(struct idr * idp)
```

```json
{
  "name": "idr_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582950304,
      "name": "idr_init",
      "external": true,
      "loc": "lib/idr.c:838",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_init"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init_subsys",
        "kernel/events/core.c:perf_event_init",
        "mm/shmem.c:shmem_fill_super",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "ipc/util.c:ipc_init_ids",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/net/ppp/ppp_generic.c:ppp_init_net",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "net/core/net_namespace.c:setup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950304,
      "name": "idr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void idr_init(struct idr * idp)
```

```json
{
  "name": "idr_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583238056,
      "name": "idr_init",
      "external": true,
      "loc": "lib/idr.c:838",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_init"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init_subsys",
        "kernel/events/core.c:perf_event_init",
        "mm/shmem.c:shmem_fill_super",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "ipc/util.c:ipc_init_ids",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/net/ppp/ppp_generic.c:ppp_init_net",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "net/core/net_namespace.c:setup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237968,
      "name": "idr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void idr_init(struct idr * idp)
```

```json
{
  "name": "idr_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583353208,
      "name": "idr_init",
      "external": true,
      "loc": "lib/idr.c:838",
      "file": "lib/idr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/idr.c:ida_init"
      ],
      "caller_func": [
        "kernel/cgroup.c:cgroup_init_subsys",
        "kernel/events/core.c:perf_event_init",
        "fs/notify/inotify/inotify_user.c:inotify_new_group",
        "ipc/util.c:ipc_init_ids",
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables",
        "drivers/net/ppp/ppp_generic.c:ppp_init_net",
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "net/core/net_namespace.c:setup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353120,
      "name": "idr_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596439305,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596462235,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580778625,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577818,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_new_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527367,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584957671,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585759517,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851743,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586984673,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:96",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
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
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602741395,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602765162,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580154131,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602789081,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580866017,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722218,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_new_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988688,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675108,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585378935,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586197485,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587339487,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587483185,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:153",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602913983,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602939027,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580213872,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602961713,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581008540,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581888107,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582176244,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582867909,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585622736,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_alloc_pasid_tables"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586454466,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587642731,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587788477,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588094497,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:138",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604711591,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604736872,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580266320,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604759963,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095532,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581973078,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582271380,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582976097,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586602194,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587771643,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587921757,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588272058,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604811910,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604838437,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317184,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604863918,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149228,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106545,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582435756,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583157553,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586856331,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588076440,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588228852,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588663706,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604846169,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604872579,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580366016,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604897771,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581207254,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582183809,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582534492,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583263617,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587002331,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605110730,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588233619,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588282248,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588433480,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588886058,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609179650,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609200488,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580438434,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609220503,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581407894,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421736,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_new_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582502518,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582840451,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583591985,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587828987,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609390031,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589106603,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589162808,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589303352,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589771050,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612245084,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612267069,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580426514,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612287632,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582475720,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_new_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582561902,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_alloc",
        "fs/io_uring.c:io_ring_ctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913203,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712337,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587886624,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612461498,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589105611,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589159736,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589302872,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589806390,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614385657,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614408277,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430946,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614427321,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582502617,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940899,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583736865,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587766448,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614603784,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588995227,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589053448,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589193938,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589710982,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615319161,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615343784,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580594962,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615366907,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582817673,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583276067,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584098625,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588362832,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615560963,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589709467,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589771334,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589914290,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590469174,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617101244,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617128969,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580797555,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617154439,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583373402,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583780045,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584693953,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589758459,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590419525,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591216855,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591281367,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591446006,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592072257,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627763554,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627800665,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082579,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627838357,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958362,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584398333,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585385073,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591407467,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592057413,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592963543,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593030615,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593214150,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593892177,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619524802,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619563691,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174276,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619602885,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584181770,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584626829,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585615745,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591822763,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592480245,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593413911,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593482311,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593674614,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594267537,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621823634,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621866507,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581279956,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:create_pid_namespace"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621906437,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584395770,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584858988,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585862465,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591946455,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/gpu/drm/drm_auth.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_auth.c:drm_master_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622181231,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/gpu/drm/drm_drv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_drv.c:drm_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592081903,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/gpu/drm/drm_lease.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622182101,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/accel/drm_accel.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/accel/drm_accel.c:accel_core_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592570747,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593224485,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/usb/host/xhci-dbgtty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-dbgtty.c:dbc_tty_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594159623,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594229463,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type",
        "drivers/powercap/powercap_sys.c:powercap_register_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594451910,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595065505,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336510879384,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510909044,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491628552,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510935876,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492590568,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493743456,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494168732,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494993780,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500110864,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501519556,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_probe",
        "drivers/firmware/arm_scmi/driver.c:scmi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501691056,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501751492,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501954876,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502475496,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243365728,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3243396568,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3225582564,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 3243425016,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3226443476,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 3227266660,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 3227608532,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 3228407212,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 3232615208,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 3234036860,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/arm_scmi/driver.c:scmi_probe",
        "drivers/firmware/arm_scmi/driver.c:scmi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3234216168,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 3234303816,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 3234712612,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 3235190336,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302510428,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302545724,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284621556,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302581308,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285899016,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287355260,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287852940,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288873428,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055293332520,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302808404,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295125448,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295199120,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295380464,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055296032940,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270620678,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270646890,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272026820,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270667348,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272626410,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273350558,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273637398,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274287340,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277070604,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278156118,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278259810,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278656402,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604751436,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604778036,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580334816,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604803228,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581176102,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582152545,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582503228,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232353,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586759355,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845315,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588040264,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588492442,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604719053,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604746951,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580282080,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604772156,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122918,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582089985,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582440444,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583169505,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586664587,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604975186,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753352,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588204442,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604829003,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604855223,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326064,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604880415,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581167302,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143025,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493708,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583216385,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586956891,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605091269,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588219304,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588372040,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588824618,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604850338,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:pid_idr_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604876721,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:init_cgroup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580381136,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/pid_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid_namespace.c:copy_pid_ns"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604901952,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581222262,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582217681,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:do_inotify_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574348,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583310417,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_init_ids"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587064331,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_init_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605114924,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588305955,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588354600,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/powercap/powercap_sys.c:powercap_register_control_type"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588507720,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:setup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588966625,
      "name": "idr_init",
      "external": false,
      "loc": "include/linux/idr.h:149",
      "file": "net/sched/cls_api.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/sched/cls_api.c:tcf_net_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void idr_init(struct idr * idp)
```
</details>
</li>
</ul>
