# Function: <code>__xa_alloc</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __xa_alloc(struct xarray * xa, u32 * id, u32 max, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433232,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1623",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433232,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890992,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1601",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890992,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116944,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116944,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585121360,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1614",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic",
        "drivers/iommu/ioasid.c:ioasid_alloc",
        "drivers/iommu/ioasid.c:default_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_region_snapshot_id_get",
        "net/core/devlink.c:devlink_nl_cmd_region_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585121360,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271920,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1804",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic",
        "drivers/iommu/ioasid.c:ioasid_alloc",
        "drivers/iommu/ioasid.c:default_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_region_snapshot_id_get",
        "net/core/devlink.c:devlink_nl_cmd_region_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271920,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155664,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1805",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic",
        "drivers/iommu/ioasid.c:ioasid_alloc",
        "drivers/iommu/ioasid.c:default_alloc",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_region_snapshot_id_get",
        "net/core/devlink.c:devlink_nl_cmd_region_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155664,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608512,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1805",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic",
        "drivers/iommu/intel/svm.c:pasid_private_add",
        "drivers/iommu/ioasid.c:ioasid_alloc",
        "drivers/iommu/ioasid.c:default_alloc",
        "drivers/base/memory.c:memory_group_register",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_region_snapshot_id_get",
        "net/core/devlink.c:devlink_nl_cmd_region_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608512,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586765168,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1812",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/secid.c:aa_alloc_secid",
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/ioasid.c:ioasid_alloc",
        "drivers/iommu/ioasid.c:default_alloc",
        "drivers/base/memory.c:memory_group_register",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_region_snapshot_id_get",
        "net/core/devlink.c:devlink_nl_cmd_region_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586765168,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595929616,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1812",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_insert_desc",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/ioasid.c:ioasid_alloc",
        "drivers/iommu/ioasid.c:default_alloc",
        "drivers/base/memory.c:memory_group_register",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "net/core/devlink.c:devlink_region_snapshot_id_get",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595929616,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596448016,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1810",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_insert_desc",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/base/memory.c:memory_group_register",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "net/devlink/leftover.c:devlink_region_snapshot_id_get",
        "net/devlink/leftover.c:devlink_nl_cmd_region_new",
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596448016,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597343376,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1813",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_insert_desc",
        "security/apparmor/secid.c:aa_alloc_secid",
        "drivers/base/memory.c:memory_group_register",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/opp/core.c:dev_pm_opp_set_config",
        "net/devlink/region.c:devlink_region_snapshot_id_get",
        "net/devlink/region.c:devlink_nl_region_new_doit",
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597343376,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503900144,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503900144,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236527892,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236527892,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297768368,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297768368,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279788090,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279788090,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589719200,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589719200,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589444976,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589444976,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590162576,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590162576,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
int __xa_alloc(struct xarray * xa, u32 * id, void * entry, struct xa_limit limit, gfp_t gfp)
```

```json
{
  "name": "__xa_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590213360,
      "name": "__xa_alloc",
      "external": true,
      "loc": "lib/xarray.c:1612",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/xarray.c:__xa_alloc_cyclic",
        "lib/xarray.c:__xa_alloc_cyclic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590213360,
      "name": "__xa_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __xa_alloc(struct xarray * xa, u32 * id, u32 max, void * entry, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xa_limit limit</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 max</code>
</li>
<li>
<b>Param reordered. </b>
<code>xa, id, max, entry, gfp</code> ➡️ <code>xa, id, entry, limit, gfp</code>
</li>
</ul>
</details>
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
