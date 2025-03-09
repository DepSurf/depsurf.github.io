# Function: <code>rb_prev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582973728,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:508",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:__free_vmap_area",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "block/elevator.c:elv_rb_former_request",
        "block/cfq-iosched.c:cfq_close_cooperator",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582973728,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583262848,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:508",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:__free_vmap_area",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "block/elevator.c:elv_rb_former_request",
        "block/cfq-iosched.c:cfq_close_cooperator",
        "block/cfq-iosched.c:cfq_find_next_rq",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262848,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583381616,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:523",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:__free_vmap_area",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "block/elevator.c:elv_rb_former_request",
        "block/cfq-iosched.c:cfq_close_cooperator",
        "block/cfq-iosched.c:cfq_find_next_rq",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583381616,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588231888,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:525",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:__free_vmap_area",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "block/elevator.c:elv_rb_former_request",
        "block/cfq-iosched.c:cfq_close_cooperator",
        "block/cfq-iosched.c:cfq_find_next_rq",
        "drivers/iommu/iova.c:alloc_iova",
        "drivers/iommu/iova.c:alloc_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231888,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588783312,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:560",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:__free_vmap_area",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "block/elevator.c:elv_rb_former_request",
        "block/cfq-iosched.c:cfq_close_cooperator",
        "block/cfq-iosched.c:cfq_find_next_rq",
        "block/cfq-iosched.c:cfq_rb_erase",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588783312,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589161584,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:560",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:__free_vmap_area",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "block/elevator.c:elv_rb_former_request",
        "block/cfq-iosched.c:cfq_close_cooperator",
        "block/cfq-iosched.c:cfq_find_next_rq",
        "block/cfq-iosched.c:cfq_rb_erase",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589161584,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589391520,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:560",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/vmalloc.c:pvm_determine_end",
        "mm/vmalloc.c:pvm_find_next_prev",
        "mm/vmalloc.c:__free_vmap_area",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391520,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589846352,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589846352,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590072448,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590072448,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585070272,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_probe_list",
        "kernel/events/uprobes.c:build_probe_list",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "mm/memcontrol.c:mem_cgroup_update_tree",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070272,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585219616,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:build_probe_list",
        "kernel/events/uprobes.c:build_probe_list",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "mm/memcontrol.c:mem_cgroup_update_tree",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all",
        "drivers/vfio/vfio_iommu_type1.c:vfio_dma_bitmap_alloc_all",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585219616,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585102512,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585102512,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585550912,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585550912,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586707408,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "drivers/vfio/vfio_iommu_type1.c:vfio_iommu_replay",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707408,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595869456,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595869456,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596386880,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap",
        "fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596386880,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597282128,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/memcontrol.c:mem_cgroup_css_free",
        "mm/memcontrol.c:memcg_check_events",
        "mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:get_rsvd",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap",
        "fs/ext4/mballoc.c:ext4_mb_pa_adjust_overlap",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:__alloc_and_insert_iova_range",
        "drivers/gpu/drm/drm_mm.c:drm_mm_insert_node_in_range",
        "net/ipv4/tcp_input.c:tcp_prune_ofo_queue",
        "net/ipv4/tcp_input.c:tcp_shift_skb_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597282128,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503851496,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503851496,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236471340,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236471340,
      "name": "rb_prev",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055297706016,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "mm/mempolicy.c:sp_lookup",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297706016,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279740282,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279740282,
      "name": "rb_prev",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674704,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674704,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589400496,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589400496,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590118080,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118080,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct rb_node * rb_prev(const struct rb_node * node)
```

```json
{
  "name": "rb_prev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590168464,
      "name": "rb_prev",
      "external": true,
      "loc": "lib/rbtree.c:524",
      "file": "lib/rbtree.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "mm/vmalloc.c:pcpu_get_vm_areas",
        "fs/ext4/block_validity.c:add_system_zone",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_remove_extent",
        "fs/ext4/extents_status.c:__es_insert_extent",
        "fs/ext4/mballoc.c:ext4_mb_free_metadata",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:mqueue_evict_inode",
        "ipc/mqueue.c:mqueue_evict_inode",
        "block/elevator.c:elv_rb_former_request",
        "drivers/iommu/iova.c:alloc_iova",
        "net/ipv4/tcp_input.c:tcp_sacktag_walk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590168464,
      "name": "rb_prev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
