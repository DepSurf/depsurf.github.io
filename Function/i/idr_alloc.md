# Function: <code>idr_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp_mask)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582952048,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:450",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:init_workqueues",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/net/ppp/ppp_generic.c:ppp_ioctl",
        "drivers/i2c/i2c-core.c:i2c_add_adapter",
        "drivers/i2c/i2c-core.c:i2c_add_numbered_adapter",
        "drivers/thermal/thermal_core.c:get_idr",
        "drivers/thermal/thermal_core.c:get_idr",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "drivers/mmc/core/host.c:mmc_alloc_host",
        "net/core/net_namespace.c:__peernet2id_alloc",
        "net/core/net_namespace.c:rtnl_net_newid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582952048,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp_mask)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583239664,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:450",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_workqueues",
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core.c:i2c_add_adapter",
        "drivers/thermal/thermal_core.c:get_idr",
        "drivers/thermal/thermal_core.c:get_idr",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583239664,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp_mask)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354816,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:450",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic",
        "drivers/dma/dmaengine.c:dma_async_device_register",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core.c:i2c_add_adapter",
        "drivers/thermal/thermal_core.c:get_idr",
        "drivers/thermal/thermal_core.c:get_idr",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354816,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588202800,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:29",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc",
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588202800,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idr_alloc",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579531479,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:alloc_unbound_pwq"
      ],
      "caller_func": [
        "kernel/workqueue.c:workqueue_init_early"
      ]
    },
    {
      "addr": 18446744071580083396,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580651697,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_pmu_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864554,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_get_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588848938,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582675283,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "ipc/util.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "ipc/util.c:ipc_addid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583451104,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "block/genhd.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583501613,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "block/bsg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bsg.c:bsg_register_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585266137,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/char/tpm/tpm-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585378281,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/iommu/intel-svm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585595205,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585969260,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/scsi/sg.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/sg.c:sg_add_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586146482,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/spi/spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_register_controller"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586210296,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/net/ppp/ppp_generic.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586300356,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/usb/core/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586786956,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586975997,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587340039,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "drivers/powercap/powercap_sys.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587481854,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "net/core/net_namespace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587803013,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "net/netlink/genetlink.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588754184,
      "name": "idr_alloc",
      "external": false,
      "loc": "include/linux/idr.h:108",
      "file": "lib/idr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/idr.c:idr_alloc_cyclic",
        "lib/idr.c:idr_alloc_cyclic"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579518192,
      "name": "idr_alloc.constprop.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589129760,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:82",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589129760,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589364416,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:78",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:dm_create",
        "drivers/md/dm.c:dm_create",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364416,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589821456,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589821456,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590047744,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590047744,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585041712,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/io_uring.c:io_provide_buffers",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585041712,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585193440,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "fs/io_uring.c:io_provide_buffers",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585193440,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076528,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "security/apparmor/secid.c:aa_alloc_secid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076528,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523360,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/vfio/vfio.c:vfio_create_group",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523360,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586676400,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586676400,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595756480,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595756480,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596280800,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/vmscan.c:__prealloc_shrinker",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596280800,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597165504,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:get_unbound_pool",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/pid.c:alloc_pid",
        "kernel/cgroup/cgroup.c:cgroup_init",
        "kernel/cgroup/cgroup.c:cgroup_init_subsys",
        "kernel/cgroup/cgroup.c:css_create",
        "kernel/events/core.c:perf_pmu_register",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shrinker.c:shrinker_alloc",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "drivers/pwm/core.c:__pwmchip_add",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_alloc",
        "drivers/gpu/drm/drm_auth.c:drm_getmagic",
        "drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group",
        "drivers/gpu/drm/drm_drv.c:drm_minor_alloc",
        "drivers/gpu/drm/drm_gem.c:drm_gem_flink_ioctl",
        "drivers/gpu/drm/drm_gem.c:drm_gem_handle_create_tail",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_lease.c:fill_object_idr",
        "drivers/gpu/drm/drm_lease.c:drm_lease_create",
        "drivers/gpu/drm/drm_mode_object.c:drm_mode_object_add",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_fd_to_handle_ioctl",
        "drivers/gpu/drm/drm_syncobj.c:drm_syncobj_get_handle",
        "drivers/accel/drm_accel.c:accel_minor_alloc",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/net/ppp/ppp_generic.c:ppp_unit_register",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "drivers/powercap/powercap_sys.c:powercap_register_zone",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597165504,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503822336,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/firmware/arm_scmi/bus.c:scmi_protocol_register",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503822336,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236443800,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/mtd/mtdcore.c:add_mtd_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/firmware/arm_scmi/bus.c:scmi_protocol_register",
        "drivers/firmware/arm_scmi/driver.c:scmi_mbox_chan_setup",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236443800,
      "name": "idr_alloc",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297666912,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/of/overlay.c:init_overlay_changeset",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297666912,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279717858,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "ipc/util.c:ipc_addid",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/i2c/i2c-core-base.c:__i2c_add_numbered_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/of/overlay.c:init_overlay_changeset",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279717858,
      "name": "idr_alloc",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589650000,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589650000,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589375808,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589375808,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590093376,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590093376,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```

```json
{
  "name": "idr_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590143632,
      "name": "idr_alloc",
      "external": true,
      "loc": "lib/idr.c:79",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:alloc_unbound_pwq",
        "kernel/workqueue.c:workqueue_init_early",
        "kernel/events/core.c:perf_pmu_register",
        "mm/shmem.c:shmem_get_inode",
        "mm/memcontrol.c:mem_cgroup_alloc",
        "ipc/util.c:ipc_addid",
        "block/bsg.c:bsg_register_queue",
        "drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make",
        "drivers/char/tpm/tpm-chip.c:tpm_chip_alloc",
        "drivers/iommu/intel-pasid.c:intel_pasid_alloc_id",
        "drivers/block/loop.c:loop_add",
        "drivers/block/loop.c:loop_add",
        "drivers/scsi/sg.c:sg_add_device",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/spi/spi.c:spi_register_controller",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/net/ppp/ppp_generic.c:ppp_dev_configure",
        "drivers/vfio/vfio.c:vfio_add_group_dev",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/i2c/i2c-core-base.c:i2c_add_numbered_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_add_adapter",
        "drivers/pps/pps.c:pps_register_cdev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/md/dm.c:alloc_dev",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:rtnl_net_newid",
        "net/core/net_namespace.c:__peernet2id_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590143632,
      "name": "idr_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_mask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int idr_alloc(struct idr * idr, void * ptr, int start, int end, gfp_t gfp)
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
