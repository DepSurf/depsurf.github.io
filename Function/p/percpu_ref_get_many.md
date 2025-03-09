# Function: <code>percpu_ref_get_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579977213,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:cgroup_get",
        "kernel/cgroup.c:init_and_link_css",
        "kernel/cgroup.c:find_css_set",
        "kernel/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010443,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978359,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ]
    },
    {
      "addr": 18446744071580922779,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:__memcg_kmem_get_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172094,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581317504,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:do_io_submit"
      ],
      "caller_func": [
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ]
    },
    {
      "addr": 18446744071582716115,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_associate_blkcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582755486,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796757,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035917,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978359,
      "name": "percpu_ref_get_many.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581317504,
      "name": "percpu_ref_get_many.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579309524,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580008363,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:init_and_link_css",
        "kernel/cgroup.c:find_css_set",
        "kernel/cgroup.c:cgroup_get",
        "kernel/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580042955,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541681,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:get_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133222,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ]
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581090349,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342407,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491886,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": [
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ]
    },
    {
      "addr": 18446744071582993059,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583033392,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583075760,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328926,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133222,
      "name": "percpu_ref_get_many.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581483632,
      "name": "percpu_ref_get_many.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324741,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580041963,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:kill_css",
        "kernel/cgroup.c:init_and_link_css",
        "kernel/cgroup.c:find_css_set",
        "kernel/cgroup.c:cgroup_get",
        "kernel/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580080964,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605729,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:get_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208309,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ]
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581165435,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421511,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581570766,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:lookup_ioctx"
      ],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ]
    },
    {
      "addr": 18446744071583098003,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583138325,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583179183,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_map_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583453535,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:168",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208309,
      "name": "percpu_ref_get_many.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071581564720,
      "name": "percpu_ref_get_many.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580060404,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580085256,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580634817,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580818772,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841930,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580880065,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__gup_device_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581213230,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476144,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581627319,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583150603,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583195130,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232247,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474312,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425323,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:169",
      "file": "drivers/md/md.c",
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579552078,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580111132,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580138152,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580717567,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580908987,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932618,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964879,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581343778,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618336,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771596,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit",
        "fs/aio.c:lookup_ioctx",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583325750,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583372390,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:blk_queue_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583409718,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655288,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594511,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586894027,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:170",
      "file": "drivers/md/md.c",
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579580781,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170323,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580199122,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580851009,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581045056,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068641,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491234,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777758,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581943421,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537845,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583581975,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583624086,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583872984,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_reinit",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585839488,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587190027,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:176",
      "file": "drivers/md/md.c",
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618413,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580218227,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249543,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580919328,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581122451,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146433,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:slab_deactivate_memcg_cache_rcu_sched"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577090,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:task_in_mem_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863559,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029052,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692596,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start",
        "block/blk-core.c:generic_make_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583729055,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583835715,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583843927,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958292,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974049,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586268851,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587369963,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:177",
      "file": "drivers/md/md.c",
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642457,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580266905,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580305156,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580912815,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187107,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213424,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548259,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688402,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_alloc",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581740226,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581988387,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582168439,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583881220,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583915999,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583946175,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584025703,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034328,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138424,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218422,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586512905,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587641291,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668425,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580315223,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580353875,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966282,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581245650,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271936,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613139,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581761793,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581813621,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582074175,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582245831,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583984372,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584019219,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049743,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584129603,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138168,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584260872,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366470,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586660857,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587845403,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699640,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580386820,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580424355,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581127946,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581434500,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581462054,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581751333,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:region_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833106,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981018,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033598,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582310484,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582482999,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517170,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:__io_async_wake"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445679,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527443,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584537137,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668200,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134406,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587457819,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588686267,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588780487,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/dm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/dm.c:dm_make_request"
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678104,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580373918,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580411816,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084464,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581162010,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581477402,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799541,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:region_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581876787,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582031227,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memcontrol.c:memcg_reparent_objcgs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081216,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582363388,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582539575,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582576749,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_sqe_files_update",
        "fs/io_uring.c:io_sqe_files_register",
        "fs/io_uring.c:io_sqe_files_unregister",
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:io_wq_submit_work",
        "fs/io_uring.c:__io_async_wake",
        "fs/io_uring.c:io_async_buf_func",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:__io_req_task_cancel",
        "fs/io_uring.c:io_fail_links",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561924,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635497,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584644941,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786085,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587220134,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587526110,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588713467,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579684569,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580376864,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580411834,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581102960,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178986,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498175,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581825349,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:region_del"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581910160,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582057959,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106357,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582391036,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582568583,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582593962,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_file_get",
        "fs/io_uring.c:io_prep_rw",
        "fs/io_uring.c:tctx_task_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584594836,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584662585,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584673181,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830149,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108470,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407774,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588598667,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760957,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580538093,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_setup_root",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580574938,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332592,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581418449,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581758177,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107959,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582204913,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582365926,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422497,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582712156,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582885863,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913901,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_init_req",
        "fs/io_uring.c:__io_splice_prep",
        "fs/io_uring.c:io_prep_rw",
        "fs/io_uring.c:tctx_task_work",
        "fs/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009524,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585077865,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585091069,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585248869,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587692015,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587979755,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589275547,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void percpu_ref_get_many(struct percpu_ref * ref, long unsigned int nr)
```

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579868342,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580735514,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580776751,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637544,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747840,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582137114,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550905,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582670627,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582863747,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582938898,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583255911,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583453654,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585675738,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725241,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806472,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585819134,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_add_bio_tg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586017973,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_wq_submit_work",
        "io_uring/io_uring.c:io_issue_sqe",
        "io_uring/io_uring.c:io_async_cancel",
        "io_uring/io_uring.c:io_splice",
        "io_uring/io_uring.c:io_tee",
        "io_uring/io_uring.c:io_prep_rw",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:handle_prev_tw_list"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_submit_sqes",
        "io_uring/io_uring.c:io_fallback_req_func"
      ]
    },
    {
      "addr": 18446744071586090609,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589029812,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589336894,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590753371,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585952240,
      "name": "percpu_ref_get_many",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580010998,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581011642,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581058554,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942968,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_ancestor",
        "kernel/bpf/helpers.c:bpf_cgroup_acquire"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026568,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143782,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162787,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582614408,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583067137,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583199459,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583411172,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583495073,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583837543,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584043542,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586452314,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586506409,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593796,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blk_cgroup_bio_start",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586601252,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586766400,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:handle_tw_list",
        "io_uring/io_uring.c:__io_alloc_req_refill",
        "io_uring/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/uring_cmd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/net.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586843653,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_rsrc_refs_refill"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/rw.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587073841,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588396686,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590558148,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903182,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592431147,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_start"
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580064646,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581100202,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581149674,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218856,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582340961,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582359715,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582823176,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583277668,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583416451,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583631428,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:charge_memcg",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:get_obj_cgroup_from_page",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583710085,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584047939,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584268262,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721827,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:__blk_mq_alloc_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586848654,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586859492,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587008687,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:__io_alloc_req_refill"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587332417,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588672673,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590886596,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591247329,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592863844,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_account_bio",
        "drivers/md/md.c:md_write_start"
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
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580107206,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197626,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_clone",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_destroy_locked",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_apply_control_disable",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_get_tree",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581253994,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058015,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374056,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461237,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507233,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526547,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997264,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583015128,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583390909,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583516788,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_vm_op_open",
        "mm/hugetlb.c:region_del",
        "mm/hugetlb.c:add_reservation_in_range",
        "mm/hugetlb.c:add_reservation_in_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583826209,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:get_obj_cgroup_from_folio",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:__refill_stock",
        "mm/memcontrol.c:mem_cgroup_get_oom_group",
        "mm/memcontrol.c:get_mem_cgroup_from_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583910437,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584262787,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_do_switch_wbs",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584485062,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586999458,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_submit_bio",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:__blk_mq_alloc_requests_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587125979,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587136948,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327663,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:tctx_task_work",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:__io_alloc_req_refill",
        "io_uring/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587615809,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588973313,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591230707,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591594590,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593613826,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:198",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_account_bio",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:md_flush_request"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void percpu_ref_get_many(struct percpu_ref * ref, long unsigned int nr)
```

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490846404,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491542592,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:find_css_set"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ]
    },
    {
      "addr": 18446603336491611108,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492314684,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492644524,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492677228,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062400,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493196076,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge"
      ]
    },
    {
      "addr": 18446603336493605716,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493816132,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495809364,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495855556,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495886580,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495978736,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495990300,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496141892,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499220244,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499561048,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501078520,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491534896,
      "name": "percpu_ref_get_many.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336493189480,
      "name": "percpu_ref_get_many",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224874204,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_associate_blkcg"
      ],
      "caller_func": []
    },
    {
      "addr": 3225533000,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 3225567588,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 3226200164,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 3226486296,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3226515732,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 3226769096,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226846720,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3227150740,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 3227325168,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 3229160996,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 3229198452,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3229231168,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 3229320328,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3229329452,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 3229463716,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 3231743216,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 3232022600,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3233587412,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283684560,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284547760,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284604832,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285554208,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285961788,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286003312,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286496872,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286728428,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286809688,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287192704,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287434048,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289995508,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290045920,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290091136,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290202780,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290214076,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290400180,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292418352,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292856016,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294571916,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271512948,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271981634,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272011370,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272441720,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272659818,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272683968,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272924938,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272991986,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273253840,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273399176,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274946918,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274979040,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275007474,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275079468,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275086884,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275197508,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276500598,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276757730,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277798650,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644745,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580284023,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580322675,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580935082,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214498,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240784,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581875,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730529,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782357,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582042911,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582214567,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583953108,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583987955,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584018479,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584098339,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584106904,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229608,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586128358,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586351337,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587476379,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573129,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580231431,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580269955,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580881146,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581161202,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187450,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523427,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669275,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581720517,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581980479,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582151463,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583890036,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583923811,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583954287,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584034771,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584042584,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164808,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972966,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586192665,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587244555,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642009,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580275271,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580313923,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926330,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581205698,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231984,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573187,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581721841,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581773669,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582034191,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582205047,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583936868,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583971715,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584002239,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082099,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584090664,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584213368,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586314438,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586608825,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587801547,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_get_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579676297,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580328876,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:cgroup_sk_alloc",
        "kernel/cgroup/cgroup.c:kill_css",
        "kernel/cgroup/cgroup.c:init_and_link_css",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:find_css_set",
        "kernel/cgroup/cgroup.c:cgroup_get_live",
        "kernel/cgroup/cgroup.c:cgroup_get_e_css"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580368824,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580986778,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268946,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581295498,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638283,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581789921,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_get_oom_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581842595,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105623,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_attach_and_unlock_inode",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582279895,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:io_submit_one",
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:ioctx_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584038757,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584075475,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_get_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584104598,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584185463,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584192899,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:throtl_qnode_add_bio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584317976,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_resurrect",
        "lib/percpu-refcount.c:__percpu_ref_switch_mode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586426118,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_rq"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586721230,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587924900,
      "name": "percpu_ref_get_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:185",
      "file": "drivers/md/md.c",
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
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void percpu_ref_get_many(struct percpu_ref * ref, long unsigned int nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void percpu_ref_get_many(struct percpu_ref * ref, long unsigned int nr)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void percpu_ref_get_many(struct percpu_ref * ref, long unsigned int nr)
```
</details>
</li>
</ul>
