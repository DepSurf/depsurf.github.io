# Function: <code>krealloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625984,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1233",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:expand_corename",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:__bioset_create",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/core/dev.c:dev_set_alias",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625984,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580731040,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1286",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:expand_corename",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:__bioset_create",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/nvdimm/label.c:init_labels",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/core/dev.c:dev_set_alias",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580731040,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580796784,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1315",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:expand_corename",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:__bioset_create",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/core/dev.c:dev_set_alias",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580796784,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580837552,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1403",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:expand_corename",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_create",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/core/dev.c:dev_set_alias",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837552,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580928240,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1445",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:expand_corename",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_create",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580928240,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063744,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1506",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063744,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581141552,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1553",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581141552,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581207600,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1643",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/dma-buf/reservation.c:reservation_object_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207600,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581266400,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581266400,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456928,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1693",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_events_inject.c:parse_entry",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:cn_vprintf",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_rule",
        "block/bio.c:bio_find_or_create_slab",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "drivers/interconnect/core.c:icc_link_create",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456928,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499680,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1101",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace_events_inject.c:parse_entry",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:format_corename",
        "fs/coredump.c:cn_vprintf",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bio_find_or_create_slab",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "drivers/interconnect/core.c:icc_link_create",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499680,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581519280,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1198",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:trace_event_format",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_inject.c:parse_entry",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:cn_vprintf",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "drivers/interconnect/core.c:icc_link_create",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581519280,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781056,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1232",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:trace_event_format",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/trace_events_inject.c:parse_entry",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:realloc_array",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:cn_vprintf",
        "fs/ext4/fast_commit.c:ext4_fc_record_regions",
        "security/apparmor/policy_unpack.c:deflate_compress",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_register_dev_region",
        "drivers/interconnect/core.c:icc_link_create",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781056,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582167888,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1209",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:trace_event_format",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:__btf_populate_kfunc_set",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:cn_vprintf",
        "fs/ext4/fast_commit.c:ext4_fc_record_regions",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_register_dev_region",
        "drivers/interconnect/core.c:icc_link_create",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582167888,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582656048,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1389",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:trace_event_format",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/bpf_trace.c:module_callback",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:push_jmp_history",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:cn_vprintf",
        "fs/ext4/fast_commit.c:ext4_fc_record_regions",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/interconnect/core.c:icc_link_create",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:slab_build_skb",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582656048,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582866160,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1397",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:trace_event_format",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/bpf_trace.c:get_modules_for_addrs",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:push_jmp_history",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:cn_vprintf",
        "fs/ext4/fast_commit.c:ext4_fc_record_regions",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup",
        "drivers/interconnect/core.c:icc_link_create",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:slab_build_skb",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582866160,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583037376,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1211",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:build_uv_gr_table",
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/trace/trace.c:trace_event_format",
        "kernel/trace/trace.c:trace_check_vprintf",
        "kernel/trace/bpf_trace.c:get_modules_for_addrs",
        "kernel/bpf/core.c:bpf_jit_add_poke_descriptor",
        "kernel/bpf/verifier.c:push_jmp_history",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/verifier.c:copy_array",
        "kernel/bpf/btf.c:register_btf_id_dtor_kfuncs",
        "kernel/bpf/btf.c:btf_populate_kfunc_set",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:cn_vprintf",
        "fs/ext4/fast_commit.c:ext4_fc_record_regions",
        "security/apparmor/policy_unpack.c:compress_zstd",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map",
        "drivers/gpio/gpiolib.c:gpiod_get_array",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_insert_to_block",
        "drivers/dax/bus.c:alloc_dev_dax_range",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state",
        "drivers/gpu/drm/drm_atomic.c:drm_atomic_get_private_obj_state",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling",
        "drivers/gpu/drm/drm_client_modeset.c:drm_client_modeset_probe",
        "drivers/gpu/drm/drm_edid.c:drm_parse_cea_ext",
        "drivers/gpu/drm/drm_edid.c:_drm_do_get_edid",
        "drivers/gpu/drm/drm_edid.c:_drm_do_get_edid",
        "drivers/gpu/drm/drm_edid.c:edid_filter_invalid_blocks",
        "drivers/gpu/drm/drm_format_helper.c:drm_fb_xrgb8888_to_mono",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/spi/spi.c:spi_map_msg",
        "drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup",
        "drivers/interconnect/core.c:icc_link_create",
        "net/core/skbuff.c:__build_skb_around",
        "net/core/skbuff.c:slab_build_skb",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_allocate_reserve_groups",
        "net/netlink/policy.c:add_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583037376,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492668264,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_build_state",
        "drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492668264,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226510360,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:add_sysfs_param",
        "kernel/params.c:add_sysfs_param",
        "kernel/trace/trace.c:create_trace_option_files",
        "kernel/bpf/verifier.c:push_jmp_history",
        "fs/xattr.c:vfs_getxattr_alloc",
        "fs/coredump.c:expand_corename",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/pinctrl/aspeed/pinctrl-aspeed.c:get_defined_attribute",
        "drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap",
        "drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_dt_subnode_to_map",
        "drivers/clk/tegra/clk-emc.c:tegra_clk_register_emc",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "sound/core/pcm_lib.c:snd_pcm_hw_rule_add",
        "sound/soc/soc-dapm.c:dapm_create_or_share_kcontrol",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226510360,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285994784,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/fadump.c:fadump_alloc_mem_ranges",
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "net/netlink/af_netlink.c:netlink_realloc_groups",
        "net/netlink/genetlink.c:genl_validate_assign_mc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285994784,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272678970,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272678970,
      "name": "krealloc",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581235248,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235248,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581181920,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181920,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226448,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226448,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
void * krealloc(const void * p, size_t new_size, gfp_t flags)
```

```json
{
  "name": "krealloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581290464,
      "name": "krealloc",
      "external": true,
      "loc": "mm/slab_common.c:1707",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "kernel/trace/trace.c:create_trace_option_files",
        "fs/xattr.c:vfs_getxattr_alloc",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "block/bio.c:bioset_init",
        "drivers/char/tpm/eventlog/efi.c:tpm_read_log_efi",
        "drivers/iommu/iommu.c:iommu_fwspec_add_ids",
        "drivers/base/regmap/regmap.c:regmap_register_patch",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write",
        "drivers/nvdimm/namespace_devs.c:nsblk_add_resource",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/spi/spi.c:__spi_pump_messages",
        "drivers/vfio/vfio.c:vfio_info_cap_add",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_register_dev_region",
        "net/netlink/af_netlink.c:netlink_realloc_groups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581290464,
      "name": "krealloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
