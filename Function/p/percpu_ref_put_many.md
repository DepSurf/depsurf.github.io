# Function: <code>percpu_ref_put_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978575,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:css_killed_work_fn",
        "kernel/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup.c:cgroup_release_root",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_subtree_control_write",
        "kernel/cgroup.c:cgroup_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580000248,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009865,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:proc_cpuset_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580413266,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580525898,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610702,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922429,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:sock_release_memcg",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:__memcg_kmem_get_cache",
        "mm/memcontrol.c:__memcg_kmem_put_cache",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580947353,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581104978,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581172143,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:wbc_detach_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581239014,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319676,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:free_ioctx_users",
        "fs/aio.c:aio_complete",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:SyS_io_getevents"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718605,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582751845,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582783821,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875390,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583035569,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_call_confirm_rcu",
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309596,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580031011,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_sk_free",
        "kernel/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup.c:css_killed_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580033023,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047656,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:proc_cpuset_show",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580449485,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485975,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580541330,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:put_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610138,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714449,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765357,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026816,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091112,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:sock_release_memcg",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581096680,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581270658,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581342046,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581405468,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581493220,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:aio_complete",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995517,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583029829,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583062147,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583162582,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583328792,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_call_confirm_rcu"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324813,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580065219,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup.c:cgroup_sk_free",
        "kernel/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup.c:css_killed_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:css_free_work_fn",
        "kernel/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_mount",
        "kernel/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580067375,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580087075,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cpuset.c:proc_cpuset_show",
        "kernel/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask",
        "kernel/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580473983,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580506509,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580547109,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580605361,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release",
        "kernel/memremap.c:put_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580677386,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580780359,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830950,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101964,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166328,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:cancel_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581171912,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581348642,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421150,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581485705,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:__blkdev_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581574992,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:aio_complete",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100509,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583134597,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583169272,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583274646,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583453706,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:267",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580060579,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580068036,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070758,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580073285,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092796,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580495004,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536221,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587245,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580635403,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710194,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580727874,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580817769,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580837840,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580879832,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages_fast",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151962,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214071,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220146,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581403983,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581475750,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581542319,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581631648,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:compat_SyS_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:aio_complete",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156605,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191272,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583226257,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329968,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474441,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445869,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:268",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579552100,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580111319,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:css_free_work_fn",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580120660,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123494,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580126021,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145852,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580549038,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580600401,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580667189,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580718016,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795720,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580812352,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580907961,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580928534,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580964695,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581273110,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344630,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581350857,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581393616,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_devmem_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581545599,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617942,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685183,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769633,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:SyS_io_cancel",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:do_io_submit",
        "fs/aio.c:SyS_io_destroy",
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:aio_complete",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331645,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583368512,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_put_request",
        "block/blk-core.c:blk_get_request_flags",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583402944,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:attempt_merge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583513232,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655418,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594891,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586912845,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:269",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579580795,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170482,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580180231,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580182820,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185708,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205403,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580696108,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756025,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580783557,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580849791,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:get_dev_pagemap",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932609,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580947395,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581043957,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581064550,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101083,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581421870,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492305,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499034,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581505218,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581542352,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_devmem_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581700271,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581777366,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581846223,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581938145,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:aio_complete",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583540797,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583578144,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_bio",
        "block/blk-core.c:__blk_put_request",
        "block/blk-core.c:blk_get_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583612126,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583727200,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583873114,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585839323,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586062923,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587190213,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:275",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618427,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580218370,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_mount",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580228295,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580231156,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234044,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257693,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580769004,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580820937,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580850254,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580917788,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "kernel/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/memremap.c:get_dev_pagemap",
        "kernel/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966390,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009194,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581025906,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581121349,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581142342,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581179163,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578147,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:memcg_kmem_uncharge",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_get_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581584874,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581590811,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581786616,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581863167,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581908716,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933652,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965418,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582024161,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:aio_complete",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583663628,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio",
        "block/bio.c:bio_reset",
        "block/bio.c:bio_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692094,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583717751,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583838890,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583850397,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583958442,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973883,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586207331,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586268929,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587370021,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:276",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642471,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580267151,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580277047,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281940,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285574,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580308764,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853372,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915513,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580953687,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057948,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072330,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581090605,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581186487,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213315,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581249461,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555156,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689383,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695920,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581704803,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581738124,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749252,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581905080,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987855,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045727,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582071284,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582098203,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582162074,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582178872,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583851686,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_endio",
        "block/bio.c:bio_reset",
        "block/bio.c:bio_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583880763,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583906179,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583946244,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584029046,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584040922,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584138573,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218251,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586445246,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586512979,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587642613,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668439,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580315471,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580325191,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330164,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333798,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357644,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580904412,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968969,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581006620,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581113708,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128314,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581147333,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581244995,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581271827,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581308069,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620148,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762807,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769384,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581778207,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581811644,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821364,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581977592,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075613,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582123503,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582148868,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175547,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582239482,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268753,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583949753,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583983915,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584009395,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584049812,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584133147,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584144756,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584261021,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366299,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586593182,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586660931,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587846709,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579699654,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580386922,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393502,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402547,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406519,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430620,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581050028,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131817,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182864,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581297664,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315979,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581328600,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433866,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581461873,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581509892,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836245,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981965,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581990141,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581994928,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582031980,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582209128,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311615,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358092,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582387764,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412464,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_final_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582473930,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582514218,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:__io_file_put_work",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_issue_sqe",
        "fs/io_uring.c:io_cleanup_req",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:__io_req_aux_free"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584342551,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584374444,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584394952,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-merge.c:blk_account_io_merge_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584414032,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584445748,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584530414,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584539402,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584668540,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134235,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587379150,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587457897,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588687717,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:300",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678123,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580374042,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580380549,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389921,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393815,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580418229,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_root_domains"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580923445,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061404,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084512,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165927,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581220793,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581341712,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356749,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581370392,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476743,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491377,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_free_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581550004,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556611,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809198,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887158,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582032231,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:memcg_expand_shrinker_maps",
        "mm/memcontrol.c:memcg_reparent_objcgs",
        "mm/memcontrol.c:obj_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582040221,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582047678,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582080292,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582256600,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582364525,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415731,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437663,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466560,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_final_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582531145,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574388,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_file_put_work",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_async_task_func",
        "fs/io_uring.c:io_poll_task_func",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_req_free_batch",
        "fs/io_uring.c:io_req_task_submit",
        "fs/io_uring.c:io_req_task_cancel",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_dismantle_req",
        "fs/io_uring.c:io_req_clean_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584458039,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584487624,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio_noacct_mq",
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584529714,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561998,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584635476,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584651351,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584786522,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587219962,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587439978,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587526150,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588714501,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579684588,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580376970,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580383495,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392849,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396759,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580420997,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580926805,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076524,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581103008,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182919,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581241227,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581360163,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373660,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581394312,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497429,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581510807,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_free_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573124,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581579424,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581754439,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837485,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917836,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kfree",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582058981,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:obj_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582066333,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582073049,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105364,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582282184,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582392173,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464399,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493579,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582558873,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582640712,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_free_work",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_put_req_deferred_cb",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:tctx_task_work",
        "fs/io_uring.c:tctx_task_work",
        "fs/io_uring.c:io_dismantle_req",
        "fs/io_uring.c:io_req_complete_post"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584492823,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584521474,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio_noacct",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584561169,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584594910,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584662564,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584678487,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830586,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108298,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587320666,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587407814,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588600709,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760937,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580538173,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580545559,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554929,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559140,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584309,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581129861,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304300,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581332640,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423527,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581482377,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581608003,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622102,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581644177,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581753474,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581772362,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837752,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581844368,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581868754,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035767,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582060122,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582088419,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128210,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582223426,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582366937,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:uncharge_page",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_charge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582376186,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582384728,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421492,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582600232,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582713825,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808171,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582875049,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x64_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x64_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582968736,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__io_uring_register",
        "fs/io_uring.c:io_uring_show_fdinfo",
        "fs/io_uring.c:__do_sys_io_uring_enter",
        "fs/io_uring.c:io_submit_sqes",
        "fs/io_uring.c:io_iopoll_complete",
        "fs/io_uring.c:io_submit_flush_completions",
        "fs/io_uring.c:ctx_flush_and_put",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_dismantle_req",
        "fs/io_uring.c:io_req_complete_post",
        "fs/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584901511,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584929083,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:blk_try_enter_queue"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584972308,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585009593,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585077844,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:bio_clone_blkg_association",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585099874,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585249435,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587691412,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_queue_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587888017,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:generic_fsdax_supported"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587979795,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589277573,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:313",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void percpu_ref_put_many(struct percpu_ref * ref, long unsigned int nr)
```

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579363621,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868318,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580735613,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743789,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753915,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580758411,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785420,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400923,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602764,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581637624,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749737,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822862,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581967565,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581985831,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582135538,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155601,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229797,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237449,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582269259,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582467601,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582498025,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:lookup_swap_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528381,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count"
      ],
      "caller_func": [
        "mm/swapfile.c:get_swap_device"
      ]
    },
    {
      "addr": 18446744071582540386,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_free_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574943,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582689888,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__kmalloc_node_track_caller",
        "mm/slub.c:__kmalloc_track_caller",
        "mm/slub.c:__kmalloc_node",
        "mm/slub.c:__kmalloc",
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_alloc_node_trace",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc_trace",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582866587,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876966,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582888199,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937093,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133643,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258064,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362134,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583442121,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585601608,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585636156,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585678692,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_mq_end_request_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585725315,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811243,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585813674,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585826686,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586015911,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:__do_sys_io_uring_enter",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_free_req",
        "io_uring/io_uring.c:__io_req_complete_put"
      ],
      "caller_func": [
        "io_uring/io_uring.c:io_uring_show_fdinfo",
        "io_uring/io_uring.c:io_req_caches_free",
        "io_uring/io_uring.c:io_fallback_req_func",
        "io_uring/io_uring.c:io_rsrc_refs_drop"
      ]
    },
    {
      "addr": 18446744071586091305,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589033748,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589336939,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590753814,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:mddev_init_writes_pending"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503008,
      "name": "percpu_ref_put_many.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071585952144,
      "name": "percpu_ref_put_many",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579434853,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010974,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581011757,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020333,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031723,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036822,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069276,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766677,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/syscall.c:bpf_map_kzalloc",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942806,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983164,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582026664,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582106800,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_alloc_destroy",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_destroy",
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143874,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144977,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582164745,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582252331,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582403661,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582421923,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524760,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:lru_gen_del_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582612802,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582635457,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582719906,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727753,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582760332,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582979950,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583012393,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio",
        "mm/swap_state.c:swap_cache_get_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583042941,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:__swap_duplicate",
        "mm/swapfile.c:__swp_swapcount",
        "mm/swapfile.c:__swap_count",
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583056018,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_free_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093426,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583222898,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583413890,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583425030,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583437940,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583497009,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583704523,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839805,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945718,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584033561,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586369720,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586407393,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586456463,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_mq_end_request_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586506483,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586592955,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_rstat_flush",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586595698,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586607502,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586756712,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_req_caches_free",
        "io_uring/io_uring.c:io_free_batch_list",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:__io_req_task_work_add",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_free_req",
        "io_uring/io_uring.c:__io_req_complete_post",
        "io_uring/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586822470,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/fdinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586842573,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/rsrc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/rsrc.c:io_rsrc_refs_drop"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587074601,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588400743,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/pci/p2pdma.c:p2pdma_page_free",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590562324,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590903227,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592431590,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:mddev_init_writes_pending"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579446907,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064622,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581100317,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108669,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581120095,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125174,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159692,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581928303,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/syscall.c:bpf_map_kvcalloc",
        "kernel/bpf/syscall.c:bpf_map_kzalloc",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127228,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174668,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582218952,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303417,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_destroy",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_destroy",
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341058,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342174,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582361673,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582452983,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582609677,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627139,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582728449,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:lru_gen_del_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582772013,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582821570,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582844687,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_alloc",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582936386,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943129,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582975914,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583191724,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220644,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583251549,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583264356,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_frontswap_store",
        "mm/zswap.c:zswap_free_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303765,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583441538,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:kmem_cache_alloc_bulk",
        "mm/slub.c:kmem_cache_free",
        "mm/slub.c:__kmem_cache_free",
        "mm/slub.c:kmem_cache_alloc_node",
        "mm/slub.c:__kmem_cache_alloc_node",
        "mm/slub.c:kmem_cache_alloc",
        "mm/slub.c:memcg_slab_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583634162,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583645430,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583662276,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712017,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583921963,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057888,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169046,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584258249,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586616408,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586654797,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586706399,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_mq_end_request_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586851158,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:blkg_free_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586854028,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586865747,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587008734,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:io_activate_pollwq_cb",
        "io_uring/io_uring.c:io_req_caches_free",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:ctx_flush_and_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587089015,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/fdinfo.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/fdinfo.c:io_uring_show_fdinfo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587333177,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588676647,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/pci/p2pdma.c:p2pdma_page_free",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590890705,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591247374,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592867622,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_end_io_acct",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:mddev_init_writes_pending",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_handle_request"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476667,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107182,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197741,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cpu_local_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206480,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581218383,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223670,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265232,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054757,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred",
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/syscall.c:bpf_map_kvcalloc",
        "kernel/bpf/syscall.c:bpf_map_kzalloc",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268332,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_release_dtor",
        "kernel/bpf/helpers.c:bpf_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582322974,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582374152,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/trampoline.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/trampoline.c:__bpf_tramp_exit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464583,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_destroy",
        "kernel/bpf/memalloc.c:bpf_mem_alloc_destroy",
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507330,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508878,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582528569,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582621687,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582781203,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799027,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582898049,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:lru_gen_del_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948146,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_swapin_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582997666,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cleanup_offline_cgwbs_workfn",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583017934,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583089584,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_test_recent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111631,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583118377,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583171732,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583376621,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:pfn_to_online_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583390447,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__memcg_slab_free_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583455965,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swap_state.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:__read_swap_cache_async",
        "mm/swap_state.c:filemap_get_incore_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583486111,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:add_swap_count_continuation",
        "mm/swapfile.c:get_swap_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583500399,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:shrink_worker",
        "mm/zswap.c:zswap_free_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583541129,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583829090,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_exit",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:__mem_cgroup_free",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:refill_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:__memcg_kmem_uncharge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:current_objcg_update",
        "mm/memcontrol.c:current_objcg_update",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:drain_local_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_handle_over_high"
      ]
    },
    {
      "addr": 18446744071583840214,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583856443,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure_dev_pagemap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912271,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page",
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584127547,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584273023,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:cleanup_offline_cgwb",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584383270,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584475033,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586886872,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_uninit"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586926058,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:bio_poll",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__submit_bio",
        "block/blk-core.c:__bio_queue_enter",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586979535,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-mq.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq.c:blk_mq_hctx_notify_offline",
        "block/blk-mq.c:blk_mq_dispatch_plug_list",
        "block/blk-mq.c:blk_mq_end_request_batch",
        "block/blk-mq.c:blk_mq_end_request_batch"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587128473,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkcg_activate_policy",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:blkg_free_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131356,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587143571,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587327710,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "io_uring/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_activate_pollwq",
        "io_uring/io_uring.c:io_activate_pollwq_cb",
        "io_uring/io_uring.c:io_req_caches_free",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:io_fallback_tw",
        "io_uring/io_uring.c:ctx_flush_and_put",
        "io_uring/io_uring.c:io_fallback_req_func"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587616569,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588977431,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/pci/p2pdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/p2pdma.c:pci_p2pmem_free_sgl",
        "drivers/pci/p2pdma.c:p2pdma_page_free",
        "drivers/pci/p2pdma.c:p2pmem_alloc_mmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591234590,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591594635,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593618117,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:326",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_end_clone_io",
        "drivers/md/md.c:md_write_start",
        "drivers/md/md.c:mddev_init",
        "drivers/md/md.c:submit_flushes",
        "drivers/md/md.c:md_end_flush",
        "drivers/md/md.c:md_handle_request",
        "drivers/md/md.c:md_handle_request"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583777248,
      "name": "percpu_ref_put_many.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void percpu_ref_put_many(struct percpu_ref * ref, long unsigned int nr)
```

```json
{
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490846356,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491534336,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:css_killed_work_fn"
      ],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ]
    },
    {
      "addr": 18446603336491583648,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491591540,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491596220,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616924,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492234948,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492318464,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492367012,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc"
      ]
    },
    {
      "addr": 18446603336492481620,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492500220,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336492643636,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492676972,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492721884,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493065720,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": [
        "mm/slub.c:alloc_slab_page"
      ]
    },
    {
      "addr": 18446603336493190272,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ]
    },
    {
      "addr": 18446603336493225668,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493283452,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493485496,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493607376,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493666936,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493700064,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493731628,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493810944,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__arm64_sys_io_cancel",
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__arm64_sys_io_destroy",
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493849568,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__arm64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495773088,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495808760,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495838872,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336495886672,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495982760,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495995348,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496141528,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499208912,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499561136,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501078648,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491538224,
      "name": "percpu_ref_put_many.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    },
    {
      "addr": 18446603336492344304,
      "name": "percpu_ref_put_many.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446603336493059776,
      "name": "percpu_ref_put_many",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    },
    {
      "addr": 18446603336493190272,
      "name": "percpu_ref_put_many",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224874252,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_associate_blkcg"
      ],
      "caller_func": []
    },
    {
      "addr": 3225533576,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 3225545312,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551404,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225555748,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573472,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 3226129180,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 3226203560,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3226237392,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 3226355704,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226372924,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226485712,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 3226515616,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3226776092,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226847948,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:drain_stock",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3226887580,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 3227049108,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227152200,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 3227197404,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3227228440,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 3227256392,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3227319032,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 3227349924,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 3229123356,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:__bio_associate_blkg"
      ],
      "caller_func": []
    },
    {
      "addr": 3229160476,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:generic_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 3229187156,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3229231268,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 3229323716,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3229335876,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 3229464080,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 3231742968,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3232022696,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 3233598576,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283684640,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284548336,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284565840,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284574252,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284580528,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284609712,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285459632,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285558272,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285620240,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285766832,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285787676,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285816896,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055285961120,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286003000,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286059328,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286506904,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286730112,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286741024,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286756196,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286807144,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286819360,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287047572,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287194700,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287263936,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287305160,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287339680,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287427656,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_compat_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_compat_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287466192,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289943628,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055289994712,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290031312,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055290091332,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290207760,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290223108,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290400536,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292417984,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292755924,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292856128,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294578320,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271512894,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271982030,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271992522,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271997814,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272001544,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272018492,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272380088,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272444176,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272472042,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272547524,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272560976,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272658976,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272683726,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272714676,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272929988,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272993016,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272999386,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273031028,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273161186,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273255274,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273292788,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273316890,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273340882,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_final_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273391982,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__se_sys_io_cancel",
        "fs/aio.c:__se_sys_io_submit",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__se_sys_io_destroy",
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273419892,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__se_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274916336,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936274946558,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274970392,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936275007600,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275082550,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275092132,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275197708,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276500424,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276757828,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277799660,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644759,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580284271,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293991,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298964,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580302598,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326444,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873212,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937769,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580975420,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581082556,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097162,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581116181,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581213843,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240675,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581276917,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588884,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581731543,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738120,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581746943,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780380,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790100,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581946328,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044349,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092239,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582117604,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144283,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582208218,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237489,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583918489,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583952651,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583978131,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584018548,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584101883,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584113492,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584229757,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586128187,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586283662,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586351411,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587477685,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573143,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580231679,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580241351,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246308,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249942,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273708,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580819340,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883833,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922467,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581029740,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044330,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581063221,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581160547,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581187341,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223564,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530384,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670243,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676760,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581685567,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581718540,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581727782,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581883896,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981901,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029759,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582055044,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081723,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582145130,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175233,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583855449,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583889579,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583914306,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583954356,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584037563,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584049172,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584164957,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972795,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586121150,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586192739,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587245845,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642023,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580275519,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285239,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290212,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293846,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317692,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580864460,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580929017,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580966668,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581073756,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088362,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581107381,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581205043,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581231875,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268117,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580196,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722855,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729432,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738255,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581771692,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581781412,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581937640,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035629,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082719,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582108084,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582134763,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582198698,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582227969,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583902249,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583936411,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583961891,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584002308,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584085643,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584097252,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584213517,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586314267,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586541150,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586608899,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587802853,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
  "name": "percpu_ref_put_many",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579676332,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580329279,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580339202,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344477,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580348202,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372621,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580922988,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989577,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_inherit",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581027754,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:perf_event_alloc",
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581135464,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150920,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited",
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169669,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581268325,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:wb_get_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581295375,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581331973,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:__get_user_pages",
        "mm/gup.c:follow_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645454,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791047,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:__mem_cgroup_clear_mc",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_uncharge",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_put_cache",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797621,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581806490,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:memory_failure"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581840558,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:get_dev_pagemap",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581850420,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582009624,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/inode.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/inode.c:__destroy_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107083,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:bdi_split_work_to_wbs",
        "fs/fs-writeback.c:wbc_detach_inode",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:inode_switch_wbs_work_fn",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:locked_inode_to_wb_and_lock_list",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155919,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582182034,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/block_dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/block_dev.c:bdev_evict_inode"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582207787,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582276922,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/aio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents",
        "fs/aio.c:__ia32_sys_io_cancel",
        "fs/aio.c:__x64_sys_io_cancel",
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:io_submit_one",
        "fs/aio.c:aio_poll_wake",
        "fs/aio.c:aio_poll_complete_work",
        "fs/aio.c:aio_poll_put_work",
        "fs/aio.c:aio_fsync_work",
        "fs/aio.c:aio_complete_rw",
        "fs/aio.c:__ia32_sys_io_destroy",
        "fs/aio.c:__x64_sys_io_destroy",
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup",
        "fs/aio.c:free_ioctx_users"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582308339,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:__ia32_sys_io_uring_enter",
        "fs/io_uring.c:__x64_sys_io_uring_enter",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:io_iopoll_getevents",
        "fs/io_uring.c:__io_free_req",
        "fs/io_uring.c:io_get_req"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584003401,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584038199,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-core.c:blk_account_io_done",
        "block/blk-core.c:direct_make_request",
        "block/blk-core.c:blk_queue_enter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584063919,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-merge.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584104680,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-mq-sched.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-mq-sched.c:blk_mq_sched_insert_requests"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584188470,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkcg_maybe_throttle_current",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584200484,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "block/blk-throttle.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-throttle.c:tg_dispatch_one_bio",
        "block/blk-throttle.c:throtl_pop_queued"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584318157,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "lib/percpu-refcount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/percpu-refcount.c:percpu_ref_kill_and_confirm",
        "lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425931,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586652862,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/dax/super.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586721324,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_end_request"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587930405,
      "name": "percpu_ref_put_many",
      "external": false,
      "loc": "include/linux/percpu-refcount.h:284",
      "file": "drivers/md/md.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/md/md.c:md_write_end"
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
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void percpu_ref_put_many(struct percpu_ref * ref, long unsigned int nr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void percpu_ref_put_many(struct percpu_ref * ref, long unsigned int nr)
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
void percpu_ref_put_many(struct percpu_ref * ref, long unsigned int nr)
```
</details>
</li>
</ul>
