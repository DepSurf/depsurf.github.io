# Function: <code>ida_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void ida_init(struct ida * ida)
```

```json
{
  "name": "ida_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582950352,
      "name": "ida_init",
      "external": true,
      "loc": "lib/idr.c:1141",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_worker_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/devpts/inode.c:devpts_mount",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582950352,
      "name": "ida_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void ida_init(struct ida * ida)
```

```json
{
  "name": "ida_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238016,
      "name": "ida_init",
      "external": true,
      "loc": "lib/idr.c:1141",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_worker_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "fs/devpts/inode.c:devpts_mount",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238016,
      "name": "ida_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
void ida_init(struct ida * ida)
```

```json
{
  "name": "ida_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583353168,
      "name": "ida_init",
      "external": true,
      "loc": "lib/idr.c:1152",
      "file": "lib/idr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:init_worker_pool",
        "fs/kernfs/dir.c:kernfs_create_root",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583353168,
      "name": "ida_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 81
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579503815,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:195",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581838960,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:195",
      "file": "fs/kernfs/dir.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/kernfs/dir.c:kernfs_create_root"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868401,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:195",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585339487,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:195",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586375421,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:195",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579530521,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:259",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582018385,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:259",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585767843,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:259",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586839869,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:259",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558061,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:237",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582206790,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:237",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586014425,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:237",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587132186,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:237",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579595229,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:292",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582301841,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:292",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585835430,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:292",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:fwnode_create_software_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586153100,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:292",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587313050,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:292",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579608936,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582468193,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586070701,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586388304,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587586886,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644600,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582567137,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586218301,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586536128,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587789233,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579675980,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875595,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218707,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586983596,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587314079,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588637073,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579655804,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948459,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585828691,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586338035,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587069167,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587376015,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587449582,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588653777,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579662268,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975681,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585707779,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586211731,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586953363,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587257151,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587331262,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588542586,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579739420,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583311281,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586187270,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:__acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586717779,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587427559,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587518371,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587826689,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587898126,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589216618,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579843660,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583818545,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587423366,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:__acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587990118,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588742871,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846179,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589177601,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589247768,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617367349,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/vfio/vfio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/vfio/vfio.c:vfio_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590679352,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579983500,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584440593,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588682229,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589355365,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590229239,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590350243,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590730969,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590807268,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592348065,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580036139,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584669377,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588969989,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589654053,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590134358,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/tty/serial/serial_base_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590549431,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590671058,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591072297,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591148368,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592774519,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:312",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580077048,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584902192,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/devpts/inode.c:devpts_fill_super"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589267492,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/acpi/scan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_device_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589964485,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/dma/dmaengine.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dma/dmaengine.c:dma_async_device_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590474021,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/tty/serial/serial_base_bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590905767,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591032417,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591417194,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591494337,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/dax/bus.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/bus.c:devm_create_dev_dax",
        "drivers/dax/bus.c:alloc_dax_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591986847,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/gpu/drm/drm_connector.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_connector.c:drm_connector_ida_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592094996,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/gpu/drm/drm_mode_config.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpu/drm/drm_mode_config.c:drmm_mode_config_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593521210,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:314",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490815544,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494212784,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336498921196,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/iommu/virtio-iommu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/iommu/virtio-iommu.c:viommu_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499027048,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499424528,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500991108,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224850344,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 3227644180,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231588728,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 3233498956,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283086200,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "arch/powerpc/platforms/powernv/vas.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/platforms/powernv/vas.c:vas_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055283647900,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287908012,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292193816,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292668652,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294464692,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271490954,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273671026,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276393340,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276651576,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277742990,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579620904,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582535873,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585978509,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586226608,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586474463,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_subsystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587420209,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579549272,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582473041,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585827773,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586044976,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586350687,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvme/host/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvme/host/core.c:nvme_init_subsystem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587188417,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618184,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526353,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586168317,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586484096,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587745377,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
  "name": "ida_init",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579651848,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "kernel/workqueue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:init_worker_pool"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582607025,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "fs/devpts/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586277597,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/base/swnode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/swnode.c:swnode_register"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586595840,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create",
        "drivers/nvdimm/region_devs.c:nd_region_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587858577,
      "name": "ida_init",
      "external": false,
      "loc": "include/linux/idr.h:309",
      "file": "drivers/thermal/thermal_core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/thermal/thermal_core.c:thermal_zone_device_register"
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
void ida_init(struct ida * ida)
```
</details>
</li>
</ul>
