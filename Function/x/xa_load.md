# Function: <code>xa_load</code>

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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589427712,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1266",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:get_dev_pagemap",
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589427712,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589885616,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1285",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589885616,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111568,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111568,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585116304,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1298",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:page_cache_readahead_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "drivers/iommu/ioasid.c:ioasid_find",
        "drivers/iommu/ioasid.c:ioasid_free",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_snapshot_id_decrement",
        "net/core/devlink.c:__devlink_snapshot_id_increment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585116304,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585266560,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1448",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/vmalloc.c:vb_free",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/io_uring.c:io_uring_flush",
        "fs/io_uring.c:io_uring_flush",
        "fs/io_uring.c:io_uring_flush",
        "fs/io_uring.c:io_uring_add_task_file",
        "fs/iomap/buffered-io.c:iomap_readahead_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "drivers/iommu/ioasid.c:ioasid_find",
        "drivers/iommu/ioasid.c:ioasid_put",
        "drivers/iommu/ioasid.c:ioasid_get",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_snapshot_id_decrement",
        "net/core/devlink.c:__devlink_snapshot_id_increment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585266560,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585149696,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1449",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/vmalloc.c:vb_free",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/io_uring.c:__io_uring_add_task_file",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_provide_buffers",
        "fs/iomap/buffered-io.c:iomap_readahead_actor",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/genhd.c:blk_lookup_devt",
        "block/partitions/core.c:add_partition",
        "drivers/iommu/ioasid.c:ioasid_find",
        "drivers/iommu/ioasid.c:ioasid_put",
        "drivers/iommu/ioasid.c:ioasid_get",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585149696,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585601696,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1449",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/vmalloc.c:vb_free",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/io_uring.c:__io_uring_add_tctx_node",
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_provide_buffers",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/genhd.c:blk_lookup_devt",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel/svm.c:pasid_to_svm_sdev",
        "drivers/iommu/ioasid.c:ioasid_find",
        "drivers/iommu/ioasid.c:ioasid_put",
        "drivers/iommu/ioasid.c:ioasid_get",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/base/memory.c:memory_group_find_by_id",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:init_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "drivers/vfio/vfio.c:vfio_assign_device_set",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585601696,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586760800,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1456",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_get_virq",
        "mm/filemap.c:__filemap_add_folio",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:__list_lru_walk_one",
        "mm/list_lru.c:list_lru_count_one",
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/vmalloc.c:vb_free",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_poll",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/genhd.c:blk_lookup_devt",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "io_uring/io_uring.c:__io_uring_register",
        "io_uring/io_uring.c:io_register_pbuf_ring",
        "io_uring/io_uring.c:__io_uring_add_tctx_node",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/io_uring.c:io_provide_buffers",
        "io_uring/io_uring.c:io_remove_buffers",
        "io_uring/io_uring.c:io_buffer_select",
        "io_uring/io_uring.c:io_kbuf_recycle",
        "drivers/xen/grant-dma-ops.c:xen_grant_setup_dma_ops",
        "drivers/iommu/intel/svm.c:prq_event_thread",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel/svm.c:pasid_to_svm_sdev",
        "drivers/iommu/ioasid.c:ioasid_find",
        "drivers/iommu/ioasid.c:ioasid_free",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/base/memory.c:memory_group_find_by_id",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:add_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/vfio/vfio.c:vfio_assign_device_set",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586760800,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595925280,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1456",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_domain_get_virq",
        "mm/filemap.c:__filemap_add_folio",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:__list_lru_walk_one",
        "mm/list_lru.c:list_lru_count_one",
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/vmalloc.c:vb_free",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_poll_classic",
        "block/blk-mq.c:blk_mq_poll_hybrid",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/genhd.c:blk_lookup_devt",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/tctx.c:__io_uring_add_tctx_node",
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_register_pbuf_ring",
        "io_uring/kbuf.c:io_provide_buffers",
        "io_uring/kbuf.c:io_remove_buffers",
        "io_uring/kbuf.c:io_buffer_select",
        "io_uring/kbuf.c:io_kbuf_recycle_legacy",
        "drivers/pci/p2pdma.c:pci_p2pdma_map_segment",
        "drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_free",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_detach_iommu",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/iommu/ioasid.c:ioasid_find",
        "drivers/iommu/ioasid.c:ioasid_free",
        "drivers/iommu/ioasid.c:ioasid_set_data",
        "drivers/base/memory.c:memblk_nr_poison_sub",
        "drivers/base/memory.c:memblk_nr_poison_inc",
        "drivers/base/memory.c:memory_group_find_by_id",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:add_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "net/core/devlink.c:devlink_health_reporter_get_from_attrs",
        "net/core/devlink.c:devlink_nl_cmd_region_read_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_new",
        "net/core/devlink.c:devlink_nl_cmd_region_del",
        "net/core/devlink.c:devlink_nl_cmd_region_get_doit",
        "net/core/devlink.c:__devlink_region_snapshot_create",
        "net/core/devlink.c:__devlink_snapshot_id_decrement",
        "net/core/devlink.c:devlink_nl_cmd_port_new_doit",
        "net/core/devlink.c:devlink_nl_pre_doit",
        "net/core/devlink.c:devlink_nl_pre_doit",
        "net/core/devlink.c:devlink_nl_pre_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595925280,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596443584,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1454",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_domain_get_virq",
        "mm/filemap.c:__filemap_add_folio",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:__list_lru_walk_one",
        "mm/list_lru.c:list_lru_count_one",
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/vmalloc.c:vmap_ram_vread_iter",
        "mm/vmalloc.c:vb_free",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_poll",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/genhd.c:part_devt",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/tctx.c:__io_uring_add_tctx_node",
        "io_uring/kbuf.c:io_pbuf_get_address",
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_register_pbuf_ring",
        "io_uring/kbuf.c:io_provide_buffers",
        "io_uring/kbuf.c:io_remove_buffers",
        "io_uring/kbuf.c:io_buffer_select",
        "io_uring/kbuf.c:io_kbuf_recycle_legacy",
        "drivers/pci/p2pdma.c:pci_p2pdma_map_segment",
        "drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_free",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_detach_iommu",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/svm.c:intel_svm_drain_prq",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/base/memory.c:memblk_nr_poison_sub",
        "drivers/base/memory.c:memblk_nr_poison_inc",
        "drivers/base/memory.c:memory_group_find_by_id",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:add_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "net/sched/cls_api.c:tcf_classify",
        "net/devlink/leftover.c:devl_param_value_changed",
        "net/devlink/leftover.c:devl_param_driverinit_value_set",
        "net/devlink/leftover.c:devl_param_driverinit_value_get",
        "net/devlink/leftover.c:devlink_param_unregister",
        "net/devlink/leftover.c:devlink_nl_cmd_region_read_dumpit",
        "net/devlink/leftover.c:devlink_nl_cmd_region_new",
        "net/devlink/leftover.c:devlink_nl_cmd_region_new",
        "net/devlink/leftover.c:devlink_nl_cmd_region_del",
        "net/devlink/leftover.c:devlink_nl_cmd_region_get_doit",
        "net/devlink/leftover.c:__devlink_region_snapshot_create",
        "net/devlink/leftover.c:__devlink_snapshot_id_decrement",
        "net/devlink/leftover.c:devlink_rate_get_from_info",
        "net/devlink/leftover.c:devlink_port_get_from_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596443584,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597338944,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1454",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:arch_memory_failure",
        "arch/x86/kernel/cpu/sgx/main.c:arch_is_platform_page",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault",
        "kernel/irq/msi.c:msi_domain_populate_irqs",
        "kernel/irq/msi.c:msi_domain_get_virq",
        "mm/filemap.c:__filemap_add_folio",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:page_cache_ra_unbounded",
        "mm/readahead.c:read_pages",
        "mm/readahead.c:read_pages",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_list_lru_alloc",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:memcg_reparent_list_lrus",
        "mm/list_lru.c:__list_lru_walk_one",
        "mm/list_lru.c:list_lru_count_one",
        "mm/list_lru.c:list_lru_putback",
        "mm/list_lru.c:list_lru_del",
        "mm/list_lru.c:list_lru_add",
        "mm/vmalloc.c:vmap_ram_vread_iter",
        "mm/vmalloc.c:vb_free",
        "mm/swap_state.c:get_shadow_from_swap_cache",
        "mm/memremap.c:get_dev_pagemap",
        "fs/mpage.c:mpage_readahead",
        "fs/iomap/buffered-io.c:iomap_readahead",
        "fs/ext4/readpage.c:ext4_mpage_readpages",
        "security/apparmor/secid.c:apparmor_secid_to_secctx",
        "block/bio.c:bioset_init",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_poll",
        "block/blk-mq.c:blk_mq_init_allocated_queue",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_map_swqueue",
        "block/blk-mq.c:blk_mq_alloc_request_hctx",
        "block/genhd.c:part_devt",
        "block/partitions/core.c:bdev_resize_partition",
        "block/partitions/core.c:bdev_del_partition",
        "block/partitions/core.c:add_partition",
        "io_uring/io_uring.c:io_init_req",
        "io_uring/tctx.c:__io_uring_add_tctx_node",
        "io_uring/kbuf.c:io_pbuf_get_address",
        "io_uring/kbuf.c:io_register_pbuf_status",
        "io_uring/kbuf.c:io_unregister_pbuf_ring",
        "io_uring/kbuf.c:io_register_pbuf_ring",
        "io_uring/kbuf.c:io_provide_buffers",
        "io_uring/kbuf.c:io_remove_buffers",
        "io_uring/kbuf.c:io_buffer_select",
        "io_uring/kbuf.c:io_kbuf_recycle_legacy",
        "drivers/pci/p2pdma.c:pci_p2pdma_map_segment",
        "drivers/xen/grant-dma-ops.c:xen_virtio_restricted_mem_acc",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_unmap_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_map_page",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_free",
        "drivers/xen/grant-dma-ops.c:xen_grant_dma_alloc",
        "drivers/iommu/intel/iommu.c:domain_setup_first_level",
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:domain_context_mapping_one",
        "drivers/iommu/intel/iommu.c:domain_detach_iommu",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/iommu.c:domain_flush_pasid_iotlb",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_nested",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level",
        "drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user",
        "drivers/iommu/intel/svm.c:intel_drain_pasid_prq",
        "drivers/iommu/intel/svm.c:intel_svm_remove_dev_pasid",
        "drivers/iommu/iommu.c:iommu_get_domain_for_dev_pasid",
        "drivers/base/memory.c:memblk_nr_poison_sub",
        "drivers/base/memory.c:memblk_nr_poison_inc",
        "drivers/base/memory.c:memory_group_find_by_id",
        "drivers/base/memory.c:memory_group_unregister",
        "drivers/base/memory.c:walk_memory_blocks",
        "drivers/base/memory.c:remove_memory_block_devices",
        "drivers/base/memory.c:create_memory_block_devices",
        "drivers/base/memory.c:add_memory_block",
        "drivers/base/memory.c:find_memory_block",
        "drivers/dax/super.c:fs_dax_get_by_bdev",
        "drivers/dpll/dpll_core.c:dpll_pin_on_pin_priv",
        "drivers/dpll/dpll_core.c:dpll_pin_on_dpll_priv",
        "drivers/dpll/dpll_core.c:dpll_device_get_by_id",
        "drivers/dpll/dpll_netlink.c:dpll_pin_pre_doit",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "net/core/page_pool_user.c:netdev_nl_page_pool_get_do",
        "net/sched/cls_api.c:tcf_classify",
        "net/netlink/genetlink.c:genl_sk_priv_get",
        "net/devlink/port.c:devlink_port_rel_cleanup_cb",
        "net/devlink/port.c:devlink_port_rel_notify_cb",
        "net/devlink/port.c:devlink_port_get_from_info",
        "net/devlink/param.c:devl_param_value_changed",
        "net/devlink/param.c:devl_param_driverinit_value_set",
        "net/devlink/param.c:devl_param_driverinit_value_get",
        "net/devlink/param.c:devlink_param_unregister",
        "net/devlink/region.c:devlink_nl_region_new_doit",
        "net/devlink/region.c:__devlink_region_snapshot_create",
        "net/devlink/region.c:__devlink_snapshot_id_decrement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597338944,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503892960,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503892960,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236521732,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236521732,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297760224,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297760224,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279783446,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279783446,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589713824,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589713824,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589439600,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589439600,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590157200,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590157200,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void * xa_load(struct xarray * xa, long unsigned int index)
```

```json
{
  "name": "xa_load",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590207712,
      "name": "xa_load",
      "external": true,
      "loc": "lib/xarray.c:1296",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/readahead.c:__do_page_cache_readahead",
        "mm/shmem.c:shmem_confirm_swap",
        "mm/memremap.c:get_dev_pagemap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590207712,
      "name": "xa_load",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void * xa_load(struct xarray * xa, long unsigned int index)
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
