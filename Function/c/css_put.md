# Function: <code>css_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978536,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
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
      "addr": 18446744071579999994,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_read",
        "kernel/cgroup_freezer.c:freezer_write"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580009859,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
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
      "addr": 18446744071580412816,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
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
      "addr": 18446744071580526095,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580610594,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
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
      "addr": 18446744071580922421,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:sock_release_memcg",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:task_in_mem_cgroup",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:__memcg_kmem_get_cache",
        "mm/memcontrol.c:__memcg_kmem_put_cache",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580947347,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182794,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582718588,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582874881,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:353",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release_rcu"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031003,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071580033017,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580047477,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071580449477,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580485246,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071580610335,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580714439,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071581091088,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:sock_release_memcg",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
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
      "addr": 18446744071581096666,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581346286,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582995500,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583162495,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580065211,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071580067369,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "kernel/cgroup_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup_freezer.c:freezer_write",
        "kernel/cgroup_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580086882,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071580473973,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580506501,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580546379,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071580677583,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580780275,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
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
      "addr": 18446744071581166304,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
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
      "addr": 18446744071581171898,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425214,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583100492,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583274559,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:352",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580060571,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
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
      "addr": 18446744071580068030,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580070681,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580073237,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580092641,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
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
      "addr": 18446744071580494992,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580536213,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580587019,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580709647,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580817759,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
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
      "addr": 18446744071580837831,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214065,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
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
      "addr": 18446744071581220140,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479609,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583156588,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583329901,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:372",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579552052,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580111307,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580120654,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580123417,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580125973,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580145697,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580549026,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580600389,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580666987,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580795167,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907951,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580928525,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581343969,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
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
      "addr": 18446744071581350780,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581621801,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583331628,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583513165,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594864,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579580745,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580170475,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580180222,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580182814,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580185671,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580205283,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580696101,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580756019,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580782384,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071580932935,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043947,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
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
      "addr": 18446744071581064541,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581491425,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
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
      "addr": 18446744071581499028,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581780452,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583540780,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "block/bio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/bio.c:bio_disassociate_task"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583727130,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:__blkg_release_rcu",
        "block/blk-cgroup.c:blkg_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585839296,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:384",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579618377,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580218363,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
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
      "addr": 18446744071580228286,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_mount"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580231150,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "kernel/cgroup/freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/freezer.c:freezer_write",
        "kernel/cgroup/freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580234007,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580257583,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
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
      "addr": 18446744071580768997,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580820931,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
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
      "addr": 18446744071580849171,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
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
      "addr": 18446744071580966380,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581009507,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581121339,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
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
      "addr": 18446744071581142333,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:kmemcg_deactivate_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581577265,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
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
      "addr": 18446744071581584868,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581867268,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581908692,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581965401,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583836137,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973856,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:386",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579642421,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580267166,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580277038,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580281932,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580285544,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580308612,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
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
      "addr": 18446744071580853365,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915496,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
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
      "addr": 18446744071580952409,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
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
      "addr": 18446744071581057876,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072576,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581186021,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
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
      "addr": 18446744071581213308,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581548307,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581688577,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581695876,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581991613,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582045706,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582098185,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584026113,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586218224,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:393",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668388,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580315486,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580325182,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580330156,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580333768,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580357492,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580904405,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580968952,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581005190,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581113636,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581128560,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244899,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581271820,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581613187,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581762001,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581769344,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582075632,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582123482,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582175529,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584130012,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366272,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579699604,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580386937,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580393493,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580402539,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580406420,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580430468,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581050021,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581131800,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581181941,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581297556,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581315480,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581433860,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581461866,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833152,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981233,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_kmem_get_cache"
      ]
    },
    {
      "addr": 18446744071581990135,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582311634,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582358071,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412444,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_final_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527760,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587134208,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953200,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579678068,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580374062,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580380543,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580389826,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580393716,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580418059,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071580923415,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581061397,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581165911,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581219868,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581341604,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356994,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581476737,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581556597,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581809188,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582032221,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582040215,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582364550,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415652,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582466540,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_final_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582579369,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/io_uring.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_free",
        "fs/io_uring.c:io_req_clean_work"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584636707,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587219937,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579684533,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580376990,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580383489,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580392754,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580396660,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580420827,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071580926775,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581076517,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581182903,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581240289,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581360084,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581373905,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581497423,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581579410,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581837479,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582058975,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
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
      "addr": 18446744071582066327,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582392198,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582493573,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584663827,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587108273,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579760900,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580538193,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580545553,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580554834,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580559016,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580584139,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581129831,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581304293,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581423511,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581481445,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581607924,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581622347,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581757431,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581844354,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128202,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582366931,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
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
      "addr": 18446744071582376180,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071582713849,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582808165,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585079323,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587691406,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:__loop_clr_fd",
        "drivers/block/loop.c:loop_queue_work"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579363450,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579868262,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580735638,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cgroup_pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580743782,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580753818,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580758266,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580785278,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581400882,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_free_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581602741,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581749711,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581821763,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
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
      "addr": 18446744071581967477,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581986103,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582136331,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582237423,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582574933,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672988,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582866481,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582876960,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583258089,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583362126,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806419,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585813556,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589033608,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:401",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589026896,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579434682,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580010918,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581011782,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581020326,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581031626,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581036657,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581069134,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581766109,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/syscall.c:bpf_map_kzalloc",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581942786,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581983141,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582105083,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582143854,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144953,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582164719,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251277,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582403557,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582422196,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582524319,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:lru_gen_del_mm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582613624,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727727,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583093418,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583202876,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583413784,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control"
      ]
    },
    {
      "addr": 18446744071583425024,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583839830,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583945710,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586588450,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586595558,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590562184,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583374464,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071590554992,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579446736,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580064566,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581100342,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581108662,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581119998,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125009,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159550,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581927677,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/syscall.c:bpf_map_kvcalloc",
        "kernel/bpf/syscall.c:bpf_map_kzalloc",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127205,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582174645,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582303402,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags",
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582341038,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582342150,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582361647,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582451977,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582609573,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582627412,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582727966,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582822392,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582943103,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583303754,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583418492,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583634056,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control"
      ]
    },
    {
      "addr": 18446744071583645424,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584057913,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584169038,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586845646,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586853958,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590890412,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592928,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071590883424,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476496,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_alloc_backing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580107126,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581197766,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_sk_free",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_get_from_fd",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_put_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_css_set_fork",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:cgroup_get_from_id",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_killed_work_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:css_free_rwork_fn",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:pressure_write",
        "kernel/cgroup/cgroup.c:cpu_local_stat_show",
        "kernel/cgroup/cgroup.c:cpu_local_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cpu_stat_show",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_kill_sb",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_do_get_tree",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock",
        "kernel/cgroup/cgroup.c:cgroup_kn_unlock"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581206470,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use",
        "kernel/cgroup/cgroup-v1.c:cgroupstats_build"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581218286,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_change_state",
        "kernel/cgroup/legacy_freezer.c:freezer_read",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581223505,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581265100,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:proc_cpuset_show",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:cpuset_hotplug_workfn",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:sched_partition_write",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:cpuset_write_resmask",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_nodemasks_hier",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_sibling_cpumasks",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:update_cpumasks_hier",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked",
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054109,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_alloc_percpu",
        "kernel/bpf/syscall.c:bpf_map_kvcalloc",
        "kernel/bpf/syscall.c:bpf_map_kzalloc",
        "kernel/bpf/syscall.c:bpf_map_kmalloc_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582268309,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:bpf_cgroup_release_dtor",
        "kernel/bpf/helpers.c:bpf_cgroup_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582322949,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582464568,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/memalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags",
        "kernel/bpf/memalloc.c:alloc_bulk"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582507310,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/cgroup_iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:bpf_iter_detach_cgroup",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini",
        "kernel/bpf/cgroup_iter.c:cgroup_iter_seq_fini"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582508854,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582528543,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "kernel/bpf/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_query",
        "kernel/bpf/cgroup.c:cgroup_bpf_link_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_detach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_prog_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582620681,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582780953,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582799300,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582897566,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
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
      "addr": 18446744071582996481,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/backing-dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_create",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn",
        "mm/backing-dev.c:cgwb_release_workfn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583089330,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_test_recent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583118351,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/mmap_lock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mmap_lock.c:get_mm_memcg_path"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387059,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583500888,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:zswap_store",
        "mm/zswap.c:shrink_worker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583541122,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:hugetlb_reserve_pages",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:alloc_hugetlb_folio",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:clear_vma_resv_huge_pages",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region",
        "mm/hugetlb.c:coalesce_file_region"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583828984,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:obj_cgroup_may_zswap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_folio",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:__mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:obj_cgroup_charge",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:__memcg_kmem_charge_page",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:obj_cgroup_uncharge_pages",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:memcg_hotplug_cpu_dead",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_oom_trylock",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_scan_tasks",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": [
        "mm/memcontrol.c:memcg_write_event_control"
      ]
    },
    {
      "addr": 18446744071583840208,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_file_region",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_counter",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_uncharge_cgroup_rsvd",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup",
        "mm/hugetlb_cgroup.c:__hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584273048,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:inode_switch_wbs",
        "fs/fs-writeback.c:__inode_attach_wb",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584383262,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587122971,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587131286,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "block/blk-cgroup-fc-appid.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid",
        "block/blk-cgroup-fc-appid.c:blkcg_set_fc_appid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591234266,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup_refcnt.h:76",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_process_work",
        "drivers/block/loop.c:loop_free_idle_workers",
        "drivers/block/loop.c:loop_free_idle_workers"
      ],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787744,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071591226960,
      "name": "css_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490846316,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491568736,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446603336491583384,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491591532,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491596172,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336491616764,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446603336492234928,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492318436,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446603336492348624,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446603336492481476,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492500560,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492643564,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446603336492676964,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493062600,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493215960,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493225608,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493607416,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493666892,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493731600,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495979308,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336499208876,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224874156,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kthread.c:kthread_associate_blkcg"
      ],
      "caller_func": []
    },
    {
      "addr": 3225533616,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 3225545300,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 3225551392,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 3225555664,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 3225573404,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 3226129168,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 3226203548,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 3226236680,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 3226355692,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226373368,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 3226485696,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 3226515604,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 3226769188,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226847172,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 3227152240,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 3227197364,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 3227256368,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 3229320808,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 3231742936,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283684488,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284548384,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 13835058055284565172,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284574240,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284580444,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055284609576,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 13835058055285459616,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285558228,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 13835058055285619820,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285766648,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285786940,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285960908,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 13835058055286002988,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286497168,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286728876,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286740936,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287194748,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287263828,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287339624,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290203512,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292417940,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271512860,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936271982084,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936271997814,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272001500,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272018412,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446743936272380072,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272444152,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446743936272471826,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/events/core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/core.c:_free_event"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272547366,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272560918,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272658976,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272925056,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272992320,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272999356,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273255322,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273292714,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273340856,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_final_destroy_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275079938,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276500390,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579644708,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580284286,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580293982,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580298956,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580302568,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580326292,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580873205,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580937752,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580973990,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581082484,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581097408,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213747,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581240668,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581923,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581730737,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581738080,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582044368,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582092218,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582144265,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584098748,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586128160,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579573092,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580231694,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580241342,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580246300,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580249912,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580273556,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580819333,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580883816,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580921046,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581029668,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581044576,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160451,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581187334,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581523476,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581669489,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581676720,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981920,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582029738,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582081705,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584035180,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972768,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579641972,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580275534,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580285230,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580290204,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580293816,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580317540,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580864453,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580929000,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580965238,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581073684,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581088608,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204947,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581231868,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581573235,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581722049,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581729392,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582035648,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582082698,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582134745,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584082508,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586314240,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
  "name": "css_put",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579676260,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/kthread.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580329310,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071580339193,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/cgroup-v1.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup-v1.c:cgroup1_get_tree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580344469,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/legacy_freezer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/legacy_freezer.c:freezer_write",
        "kernel/cgroup/legacy_freezer.c:freezer_read"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580348172,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/cgroup/rdma.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/rdma.c:rdmacg_uncharge_hierarchy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580372477,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071580922981,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:cgroup_fd_array_put_ptr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580989560,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581026278,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581135394,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150346,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:balance_dirty_pages_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581268230,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
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
      "addr": 18446744071581295368,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slab_common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slab_common.c:memcg_deactivate_kmem_caches",
        "mm/slab_common.c:destroy_memcg_params"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581638364,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790225,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_sk_free",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_write_event_control",
        "mm/memcontrol.c:memcg_event_remove",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:mem_cgroup_soft_limit_reclaim",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:memcg_kmem_cache_create_func",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_oom_synchronize",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581797568,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "mm/hugetlb_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb_cgroup.c:hugetlb_cgroup_charge_cgroup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582107122,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/fs-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:cgroup_writeback_by_id",
        "fs/fs-writeback.c:__inode_attach_wb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582155898,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/buffer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/buffer.c:alloc_page_buffers"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582207769,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "fs/notify/group.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/group.c:fsnotify_put_group"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584185956,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "block/blk-cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "block/blk-cgroup.c:blkg_create",
        "block/blk-cgroup.c:__blkg_release"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586425904,
      "name": "css_put",
      "external": false,
      "loc": "include/linux/cgroup.h:395",
      "file": "drivers/block/loop.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:lo_rw_aio_complete"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void css_put(struct cgroup_subsys_state * css)
```
</details>
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
