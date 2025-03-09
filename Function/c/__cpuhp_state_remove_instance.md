# Function: <code>__cpuhp_state_remove_instance</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407216,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1536",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "net/core/flow.c:flow_cache_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407216,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579394176,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1490",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "net/core/flow.c:flow_cache_fini"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579394176,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579421952,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1678",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579421952,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436720,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1760",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436720,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579469680,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1782",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579469680,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487536,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1808",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487536,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513472,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513472,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579542208,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1954",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:__padata_free",
        "kernel/padata.c:__padata_free",
        "mm/zswap.c:zswap_pool_destroy",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542208,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579523920,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1965",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "fs/io-wq.c:__io_wq_destroy",
        "fs/io-wq.c:io_wq_create",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579523920,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579527568,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:2068",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_create",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/iommu/iova.c:put_iova_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579527568,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:2099",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "fs/io-wq.c:io_wq_put_and_exit",
        "fs/io-wq.c:io_wq_create",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/iommu/iova.c:put_iova_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592099402,
      "name": "__cpuhp_state_remove_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579599504,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:2121",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593866937,
      "name": "__cpuhp_state_remove_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579691744,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:2145",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595973572,
      "name": "__cpuhp_state_remove_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579815632,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:2530",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "io_uring/io-wq.c:io_wq_create",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_unregister",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_cpu_notif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596491178,
      "name": "__cpuhp_state_remove_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579863536,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:2576",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:zswap_pool_destroy",
        "block/bio.c:bioset_exit",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_init_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "io_uring/io-wq.c:io_wq_put_and_exit",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_unregister",
        "drivers/iommu/intel/perfmon.c:iommu_pmu_register",
        "drivers/iommu/iova.c:put_iova_domain",
        "drivers/nvdimm/nd_perf.c:register_nvdimm_pmu",
        "drivers/nvdimm/nd_perf.c:nvdimm_pmu_free_hotplug_memory",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_freeze",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_remove",
        "drivers/net/virtio_net.c:virtnet_cpu_notif_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597387902,
      "name": "__cpuhp_state_remove_instance.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071579901440,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 485
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490649968,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/perf/arm-ccn.c:arm_ccn_remove",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm_pmu.c:armpmu_register",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_remove",
        "drivers/perf/hisilicon/hisi_uncore_l3c_pmu.c:hisi_l3c_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_remove",
        "drivers/perf/hisilicon/hisi_uncore_hha_pmu.c:hisi_hha_pmu_probe",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_remove",
        "drivers/perf/hisilicon/hisi_uncore_ddrc_pmu.c:hisi_ddrc_pmu_probe",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_remove",
        "drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_probe",
        "drivers/perf/xgene_pmu.c:xgene_pmu_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490649968,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224726504,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_probe",
        "arch/arm/mach-imx/mmdc.c:imx_mmdc_remove",
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/perf/arm-ccn.c:arm_ccn_remove",
        "drivers/perf/arm-ccn.c:arm_ccn_probe",
        "drivers/perf/arm_pmu.c:armpmu_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224726504,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283471296,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283471296,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 616
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271398780,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271398780,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 290
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487136,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487136,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416016,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416016,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579487056,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579487056,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```

```json
{
  "name": "__cpuhp_state_remove_instance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519200,
      "name": "__cpuhp_state_remove_instance",
      "external": true,
      "loc": "kernel/cpu.c:1823",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ring_buffer.c:ring_buffer_free",
        "kernel/padata.c:padata_sysfs_release",
        "kernel/padata.c:padata_sysfs_release",
        "mm/zswap.c:__zswap_pool_release",
        "block/blk-mq.c:blk_mq_realloc_hw_ctxs",
        "block/blk-mq.c:blk_mq_exit_hctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519200,
      "name": "__cpuhp_state_remove_instance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 367
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int __cpuhp_state_remove_instance(enum cpuhp_state state, struct hlist_node * node, bool invoke)
```
</details>
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
