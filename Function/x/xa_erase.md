# Function: <code>xa_erase</code>

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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589434320,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1324",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589434320,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589892384,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1342",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892384,
      "name": "xa_erase",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590118336,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118336,
      "name": "xa_erase",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585121920,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1355",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/ioasid.c:ioasid_free",
        "drivers/iommu/ioasid.c:default_free",
        "drivers/base/memory.c:unregister_memory",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585121920,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585272480,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1505",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "fs/io_uring.c:io_uring_flush",
        "fs/io_uring.c:io_uring_remove_task_files",
        "drivers/iommu/ioasid.c:ioasid_put",
        "drivers/iommu/ioasid.c:default_free",
        "drivers/base/memory.c:unregister_memory",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272480,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585154176,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1506",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_del_task_file",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_provide_buffers",
        "block/bio.c:bioset_exit",
        "block/partitions/core.c:delete_partition",
        "drivers/iommu/ioasid.c:ioasid_put",
        "drivers/iommu/ioasid.c:default_free",
        "drivers/base/memory.c:unregister_memory",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585154176,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607024,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1506",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "mm/vmalloc.c:free_vmap_block",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_del_tctx_node",
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_provide_buffers",
        "block/bio.c:bioset_exit",
        "block/partitions/core.c:delete_partition",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid",
        "drivers/iommu/ioasid.c:ioasid_put",
        "drivers/iommu/ioasid.c:default_free",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:unregister_memory",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_free",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607024,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586763136,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1513",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_free_msi_descs_range",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:delete_partition",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_uring_del_tctx_node",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/io_uring.c:io_ring_ctx_free",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/ioasid.c:ioasid_free",
        "drivers/iommu/ioasid.c:default_free",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/dax/super.c:dax_remove_host",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "net/core/devlink.c:devlink_free",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763136,
      "name": "xa_erase",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595927472,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1513",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_free_descs",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:delete_partition",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/tctx.c:io_uring_del_tctx_node",
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_destroy_buffers",
        "drivers/iommu/intel/iommu.c:domain_detach_iommu",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/iommu/ioasid.c:ioasid_free",
        "drivers/iommu/ioasid.c:default_free",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/dax/super.c:dax_remove_host",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/opp/core.c:devm_pm_opp_set_config",
        "net/core/devlink.c:devl_port_unregister",
        "net/core/devlink.c:devlink_free",
        "net/core/devlink.c:devlink_alloc_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595927472,
      "name": "xa_erase",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596445872,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1511",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_free_descs",
        "mm/vmalloc.c:free_vmap_block",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:bdev_disk_changed",
        "block/partitions/core.c:bdev_del_partition",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_ring_ctx_wait_and_kill",
        "io_uring/tctx.c:io_uring_del_tctx_node",
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_destroy_buffers",
        "drivers/iommu/intel/iommu.c:domain_detach_iommu",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/dax/super.c:dax_remove_host",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/opp/core.c:devm_pm_opp_set_config",
        "net/sched/cls_api.c:tcf_exts_destroy",
        "net/devlink/leftover.c:devlink_param_unregister",
        "net/devlink/leftover.c:devl_port_unregister",
        "net/devlink/core.c:devlink_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596445872,
      "name": "xa_erase",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597341232,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1511",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_free_descs",
        "mm/vmalloc.c:free_vmap_block",
        "fs/libfs.c:simple_offset_rename_exchange",
        "fs/libfs.c:simple_offset_rename_exchange",
        "fs/libfs.c:simple_offset_rename_exchange",
        "fs/libfs.c:simple_offset_rename_exchange",
        "fs/libfs.c:simple_offset_rename_exchange",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/genhd.c:__alloc_disk_node",
        "block/partitions/core.c:bdev_disk_changed",
        "block/partitions/core.c:bdev_del_partition",
        "io_uring/tctx.c:io_uring_del_tctx_node",
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_destroy_buffers",
        "io_uring/register.c:io_unregister_personality",
        "drivers/iommu/intel/iommu.c:domain_detach_iommu",
        "drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid",
        "drivers/iommu/iommu.c:iommu_detach_device_pasid",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:remove_memory_block",
        "drivers/dax/super.c:dax_remove_host",
        "drivers/dma-buf/dma-heap.c:dma_heap_add",
        "drivers/opp/core.c:devm_pm_opp_set_config",
        "drivers/dpll/dpll_core.c:dpll_pin_put",
        "drivers/dpll/dpll_core.c:dpll_device_put",
        "drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add",
        "drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add",
        "net/core/dev.c:register_netdevice",
        "net/core/dev.c:unlist_netdevice",
        "net/core/page_pool_user.c:page_pool_unlist",
        "net/sched/cls_api.c:tcf_exts_destroy",
        "net/sched/cls_api.c:tcf_block_put_ext",
        "net/netlink/genetlink.c:genl_release",
        "net/devlink/core.c:devlink_free",
        "net/devlink/core.c:__devlink_rel_put",
        "net/devlink/dev.c:devlink_rel_cleanup_cb",
        "net/devlink/port.c:devl_port_unregister",
        "net/devlink/param.c:devlink_param_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597341232,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503898512,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503898512,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236526652,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236526652,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297766704,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297766704,
      "name": "xa_erase",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279786630,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279786630,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589720592,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589720592,
      "name": "xa_erase",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446368,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446368,
      "name": "xa_erase",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590163968,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163968,
      "name": "xa_erase",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * xa_erase(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_erase",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212320,
      "name": "xa_erase",
      "external": true,
      "loc": "lib/xarray.c:1353",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590212320,
      "name": "xa_erase",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void * xa_erase(struct xarray * xa, long unsigned int index)
```
</details>
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
