# Function: <code>idr_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void idr_remove(struct idr * idp, int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582949312,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:550",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/cgroup.c:cgroup_idr_remove",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "ipc/util.c:ipc_rmid",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "lib/idr.c:ida_remove",
        "drivers/dma/dmaengine.c:chan_dev_release",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/dm.c:free_minor",
        "drivers/mmc/core/host.c:mmc_host_classdev_release",
        "net/core/net_namespace.c:cleanup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582949312,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 597
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
void idr_remove(struct idr * idp, int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583237008,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:550",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/cgroup.c:css_release_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "ipc/util.c:ipc_rmid",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "lib/idr.c:ida_remove",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:chan_dev_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/dm.c:free_minor",
        "net/core/net_namespace.c:cleanup_net"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583237008,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 564
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
void idr_remove(struct idr * idp, int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583352160,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:550",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/cgroup.c:css_release_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_setup_root",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "ipc/util.c:ipc_rmid",
        "block/bsg.c:bsg_register_queue",
        "block/bsg.c:bsg_unregister_queue",
        "lib/idr.c:ida_remove",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/dma/dmaengine.c:chan_dev_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/thermal/thermal_core.c:thermal_zone_device_unregister",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_unbind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/thermal/thermal_core.c:thermal_zone_bind_cooling_device",
        "drivers/md/dm.c:free_minor",
        "net/core/net_namespace.c:cleanup_net",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583352160,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 566
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
  "name": "idr_remove",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500707,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580032198,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_release_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580490089,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580557084,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580791666,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588284001,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578183,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582527829,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_rmid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583270200,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583318235,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_register_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844329,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584955912,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585168435,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585530113,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585763256,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585854939,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_deregister_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586321488,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586502328,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:free_minor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851063,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586986232,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587284339,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:91",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
  "name": "idr_remove",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579528641,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:put_unbound_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579541668,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "kernel/pid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580106011,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580543151,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580638082,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580881266,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849239,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722583,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "fs/notify/inotify/inotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983960,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582676006,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583448984,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583501950,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_register_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585265017,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585377106,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585596163,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585961745,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586137819,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586209192,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586294795,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_deregister_bus"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586785238,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586969768,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:free_minor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338807,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587484600,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:cleanup_net"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587804499,
      "name": "idr_remove",
      "external": false,
      "loc": "include/linux/idr.h:148",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589130048,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:155",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_free_secid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:free_dev",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:tcf_block_get_ext",
        "net/sched/act_api.c:tcf_idr_create",
        "net/sched/act_api.c:__tcf_idr_release",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589130048,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364704,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:151",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:free_dev",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364704,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821728,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821728,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590048016,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590048016,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585041984,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_remove_personalities",
        "fs/io_uring.c:__io_destroy_buffers",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_provide_buffers",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_free_secid",
        "block/genhd.c:disk_release",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:unhash_nsid",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:tcf_idr_delete_index",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585041984,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193712,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_remove_personalities",
        "fs/io_uring.c:__io_destroy_buffers",
        "fs/io_uring.c:io_provide_buffers",
        "fs/io_uring.c:io_remove_buffers",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_free_secid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:unhash_nsid",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:tcf_idr_delete_index",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193712,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076800,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:free_prealloced_shrinker",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_free_secid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_action_delete",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076800,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523632,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_free_id",
        "kernel/bpf/syscall.c:bpf_prog_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:free_prealloced_shrinker",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_free_secid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/vfio/vfio.c:vfio_group_release",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:tcf_del_walker",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523632,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676704,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_free_id",
        "kernel/bpf/syscall.c:bpf_prog_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:free_prealloced_shrinker",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_remove",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676704,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595756816,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:free_prealloced_shrinker",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_del_notify",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595756816,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596281136,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:free_prealloced_shrinker",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596281136,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597165840,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_destroy_root",
        "kernel/bpf/syscall.c:bpf_raw_tp_link_attach",
        "kernel/bpf/syscall.c:bpf_perf_link_attach",
        "kernel/bpf/syscall.c:bpf_tracing_prog_attach",
        "kernel/bpf/syscall.c:bpf_link_prime",
        "kernel/bpf/syscall.c:bpf_link_free",
        "kernel/bpf/syscall.c:bpf_prog_put_deferred",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shrinker.c:shrinker_free",
        "mm/shrinker.c:shrinker_alloc",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_exit",
        "drivers/block/loop.c:loop_control_ioctl",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/gpu/drm/drm_auth.c:drm_master_release",
        "drivers/gpu/drm/drm_connector.c:drm_connector_cleanup",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_delete",
        "drivers/gpu/drm/drm_gem.c:drm_gem_object_handle_put_unlocked",
        "drivers/gpu/drm/drm_lease.c:_drm_lease_revoke",
        "drivers/gpu/drm/drm_lease.c:drm_lease_destroy",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_object_unregister",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_destroy_ioctl",
        "drivers/accel/drm_accel.c:accel_minor_remove",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_del_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:__dm_destroy",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "drivers/interconnect/core.c:icc_node_destroy",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/cls_api.c:__tcf_block_put",
        "net/sched/act_api.c:tcf_action_reoffload_cb",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597165840,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503822680,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_minor",
        "drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_free_channel",
        "drivers/of/overlay.c:free_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503822680,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236444180,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/mtd/mtdcore.c:del_mtd_device",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_minor",
        "drivers/firmware/arm_scmi/bus.c:scmi_protocol_unregister",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_free_channel",
        "drivers/of/overlay.c:free_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236444180,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297667456,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_minor",
        "drivers/of/overlay.c:free_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297667456,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279718088,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_minor",
        "drivers/of/overlay.c:free_overlay_changeset",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/sched/act_api.c:__tcf_action_put",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279718088,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650272,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650272,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589376080,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376080,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093648,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093648,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
void * idr_remove(struct idr * idr, long unsigned int id)
```

```json
{
  "name": "idr_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590143904,
      "name": "idr_remove",
      "external": true,
      "loc": "lib/idr.c:152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:put_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/pid.c:free_pid",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:cgroup_idr_remove",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/bpf/syscall.c:bpf_map_free_id",
        "kernel/events/core.c:perf_pmu_unregister",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_evict_inode",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/notify/inotify/inotify_user.c:inotify_remove_from_idr",
        "fs/kernfs/dir.c:__kernfs_new_node",
        "ipc/util.c:ipc_rmid",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_release",
        "drivers/char/tpm/tpm-chip.c:tpm_dev_release",
        "drivers/iommu/intel-pasid.c:intel_pasid_free_id",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_device_destroy",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_unregister_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_uninit",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/vfio/vfio.c:vfio_group_put",
        "drivers/usb/core/hcd.c:usb_deregister_bus",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/pps/pps.c:pps_device_destruct",
        "drivers/md/dm.c:free_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_free_vring",
        "drivers/powercap/powercap_sys.c:powercap_release",
        "net/core/net_namespace.c:cleanup_net",
        "net/sched/act_api.c:tca_action_gd",
        "net/sched/act_api.c:tcf_idr_cleanup",
        "net/netlink/genetlink.c:genl_unregister_family"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143904,
      "name": "idr_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void idr_remove(struct idr * idp, int id)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * idr_remove(struct idr * idr, long unsigned int id)
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
