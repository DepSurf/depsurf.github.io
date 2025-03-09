# Function: <code>mem_cgroup_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580482269,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:350",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580550329,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:350",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:shrink_zone",
        "mm/vmscan.c:mem_cgroup_shrink_node_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580593682,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:350",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580675101,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:350",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580915129,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:350",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_css_online",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_zone_lruvec",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_replace_page",
        "mm/memcontrol.c:mem_cgroup_commit_charge"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581326834,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:350",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:__dax_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580564035,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580665488,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580684140,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580762941,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580789381,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581091270,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_out_of_memory",
        "mm/memcontrol.c:mem_cgroup_iter"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581499080,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580630431,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580732757,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580751211,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580828557,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580853753,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166486,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_get_limit",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581583397,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:280",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579374306,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580657852,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580669046,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710508,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580722980,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580768743,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580786121,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869966,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580895579,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958263,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099665,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581214295,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_get_limit",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645064,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401170,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580737655,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580754075,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580796059,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580808793,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580856088,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580875438,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960926,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580993464,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060007,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210334,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581344919,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_low",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_get_limit",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581790805,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:270",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579414355,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580875775,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892320,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936024,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580945943,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580992532,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581012561,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095525,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581139617,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581198636,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356711,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603003141,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581964953,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:309",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448864,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580950106,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580961075,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003851,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581022092,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581069684,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:move_active_pages_to_lru",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086110,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/shmem.c:shmem_getpage_gfp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174393,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581215825,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581281984,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442009,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604802116,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582046788,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:331",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581039754,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581057190,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068236,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133129,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151681,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581244857,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581289206,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356590,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581555063,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604905413,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582211185,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:333",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581095262,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112888,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124204,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581190873,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581209570,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581303305,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581347926,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581416150,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581620055,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604939372,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582292081,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool mem_cgroup_disabled()
```

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581283636,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page",
        "mm/filemap.c:unaccount_page_cache_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581296779,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310859,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581333905,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581375325,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581391933,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_delete_from_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492937,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581552178,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581618251,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_remove_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_anon_compound_rmap",
        "mm/rmap.c:page_remove_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581836148,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581878883,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581901984,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581933565,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982760,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swap_init"
      ]
    },
    {
      "addr": 18446744071582575334,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:337",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581983594,
      "name": "mem_cgroup_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool mem_cgroup_disabled()
```

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581304864,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581340706,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581362284,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581378785,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581401526,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:age_active_anon",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581426832,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581518813,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581534809,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595318,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581604518,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581887074,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
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
      "addr": 18446744071581922375,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944592,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033080,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:lock_page_lruvec_irqsave",
        "mm/memcontrol.c:lock_page_lruvec_irq",
        "mm/memcontrol.c:lock_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swap_init"
      ]
    },
    {
      "addr": 18446744071582637856,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:521",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581991392,
      "name": "mem_cgroup_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool mem_cgroup_disabled()
```

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581322880,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581359198,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581380315,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581399713,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425581,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:prealloc_shrinker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581454528,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581538889,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581556636,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581615798,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581626983,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581917749,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
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
      "addr": 18446744071581950146,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581970577,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059864,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_charge",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:lock_page_lruvec_irqsave",
        "mm/memcontrol.c:lock_page_lruvec_irq",
        "mm/memcontrol.c:lock_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swap_init"
      ]
    },
    {
      "addr": 18446744071582674016,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:611",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019392,
      "name": "mem_cgroup_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool mem_cgroup_disabled()
```

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581535267,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581581699,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:__add_to_page_cache_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581607054,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581617019,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581650314,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost_page",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:pagevec_lru_move_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581673955,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:prealloc_shrinker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581705442,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581799200,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581820492,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581882729,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581895541,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_pagevec"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013141,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582072584,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582090951,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:get_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582195537,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582254774,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:migrate_page_move_mapping",
        "mm/migrate.c:migrate_page_move_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582273274,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582311449,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367384,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:lock_page_lruvec_irqsave",
        "mm/memcontrol.c:lock_page_lruvec_irq",
        "mm/memcontrol.c:lock_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swap_init"
      ]
    },
    {
      "addr": 18446744071582368725,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582379193,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582412879,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582424790,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_devmap_managed_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583001376,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:602",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582321664,
      "name": "mem_cgroup_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
bool mem_cgroup_disabled()
```

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581884081,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581944058,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581966282,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581987704,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582019228,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_lru_add",
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:__folio_activate",
        "mm/swap.c:lru_note_cost_folio",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:pagevec_lru_move_fn",
        "mm/swap.c:__put_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582054651,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_pages",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:prepare_kswapd_sleep",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_page_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:prealloc_shrinker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582091196,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582190342,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582211740,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582284921,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582297865,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582411709,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582439904,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582512595,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582530933,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582658929,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582720023,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582744043,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582753282,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582796600,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865325,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_page",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:folio_lruvec_lock_irqsave",
        "mm/memcontrol.c:folio_lruvec_lock_irq",
        "mm/memcontrol.c:folio_lruvec_lock",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_swap_init"
      ]
    },
    {
      "addr": 18446744071582867445,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582880467,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582926286,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582940179,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474005,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:582",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582814416,
      "name": "mem_cgroup_disabled",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582317326,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582378239,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582402298,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582415337,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582447865,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost_refault",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582509606,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:prepare_kswapd_sleep",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:get_nr_to_scan",
        "mm/vmscan.c:get_nr_to_scan",
        "mm/vmscan.c:get_nr_to_scan",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:should_run_aging",
        "mm/vmscan.c:should_run_aging",
        "mm/vmscan.c:try_to_inc_max_seq",
        "mm/vmscan.c:try_to_inc_max_seq",
        "mm/vmscan.c:try_to_inc_max_seq",
        "mm/vmscan.c:try_to_inc_max_seq",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:walk_pte_range",
        "mm/vmscan.c:iterate_mm_list",
        "mm/vmscan.c:iterate_mm_list",
        "mm/vmscan.c:lru_gen_migrate_mm",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:__prealloc_shrinker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582565737,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582677367,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582699740,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_eviction",
        "mm/workingset.c:lru_gen_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582777449,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792506,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_page",
        "mm/mlock.c:__mlock_new_page",
        "mm/mlock.c:__mlock_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582918986,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vunmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582948960,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583031571,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583045422,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583182314,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583243090,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583275714,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583286103,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583340009,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627895093,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mem_cgroup_from_slab_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:lock_page_memcg",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:folio_lruvec_lock_irqsave",
        "mm/memcontrol.c:folio_lruvec_lock_irq",
        "mm/memcontrol.c:folio_lruvec_lock",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583414821,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583417221,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapoff",
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583430035,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583482535,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mcopy_atomic"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583496781,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584066546,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:560",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582518477,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582586871,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582608333,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582621321,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582652953,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost_refault",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582712077,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:prepare_kswapd_sleep",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lruvec_is_sizable",
        "mm/vmscan.c:lruvec_is_sizable",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:walk_pte_range",
        "mm/vmscan.c:lru_gen_migrate_mm",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:prepare_scan_count",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_folio_list",
        "mm/vmscan.c:shrink_slab",
        "mm/vmscan.c:shrink_slab_memcg",
        "mm/vmscan.c:__prealloc_shrinker"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582772117,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582887754,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582913740,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_eviction",
        "mm/workingset.c:lru_gen_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582993775,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_cow_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583010243,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583135003,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vfree"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166096,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_compound_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583240435,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583254030,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583399785,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583463284,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583492080,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583504175,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583553695,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619658021,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mem_cgroup_from_slab_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:folio_lruvec_lock_irqsave",
        "mm/memcontrol.c:folio_lruvec_lock_irq",
        "mm/memcontrol.c:folio_lruvec_lock",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__mod_lruvec_page_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583635109,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583637541,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapoff",
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651758,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583699249,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583711789,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584292933,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:573",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582687382,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "kernel/events/uprobes.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:__replace_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582758270,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_add_folio",
        "mm/filemap.c:__filemap_add_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582779709,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582792518,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:folio_account_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582824100,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/swap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap.c:release_pages",
        "mm/swap.c:release_pages",
        "mm/swap.c:lru_deactivate_file_fn",
        "mm/swap.c:lru_note_cost_refault",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:lru_note_cost",
        "mm/swap.c:folio_batch_move_lru",
        "mm/swap.c:__folio_put"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582881269,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:check_move_unevictable_folios",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:prepare_kswapd_sleep",
        "mm/vmscan.c:mem_cgroup_shrink_node",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:do_try_to_free_pages",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:shrink_node_memcgs",
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:run_cmd",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_show",
        "mm/vmscan.c:lru_gen_seq_next",
        "mm/vmscan.c:lru_gen_seq_stop",
        "mm/vmscan.c:lru_gen_shrink_node",
        "mm/vmscan.c:lru_gen_shrink_node",
        "mm/vmscan.c:shrink_many",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:shrink_one",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:try_to_shrink_lruvec",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:evict_folios",
        "mm/vmscan.c:scan_folios",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_look_around",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lru_gen_age_node",
        "mm/vmscan.c:lruvec_is_sizable",
        "mm/vmscan.c:lruvec_is_sizable",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:walk_mm",
        "mm/vmscan.c:walk_pte_range",
        "mm/vmscan.c:lru_gen_migrate_mm",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_swappiness",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:prepare_scan_control",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:inactive_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_folio_list"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925811,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/shrinker.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shrinker.c:shrinker_alloc",
        "mm/shrinker.c:shrink_slab",
        "mm/shrinker.c:shrink_slab_memcg"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582964205,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_alloc_and_add_folio",
        "mm/shmem.c:shmem_add_to_page_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583060184,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/compaction.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/compaction.c:isolate_migratepages_block"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583088029,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_test_recent",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:workingset_age_nonresident",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_refault",
        "mm/workingset.c:lru_gen_eviction",
        "mm/workingset.c:lru_gen_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583175647,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_fault",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583189371,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/mlock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mlock.c:__munlock_folio",
        "mm/mlock.c:__mlock_new_folio",
        "mm/mlock.c:__mlock_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583318059,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583349622,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:destroy_large_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583474963,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/swapfile.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swapfile.c:swapcache_free_entries",
        "mm/swapfile.c:put_swap_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583488520,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/swap_slots.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_slots.c:folio_alloc_swap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583494522,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/zswap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/zswap.c:shrink_memcg",
        "mm/zswap.c:shrink_memcg_cb",
        "mm/zswap.c:zswap_shrinker_count",
        "mm/zswap.c:zswap_shrinker_scan",
        "mm/zswap.c:zswap_lru_add",
        "mm/zswap.c:zswap_folio_swapin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583526726,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:free_huge_folio"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639764,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/ksm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/ksm.c:ksm_might_need_to_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583656466,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:folio_migrate_mapping",
        "mm/migrate.c:folio_migrate_mapping"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583683145,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/migrate_device.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate_device.c:migrate_vma_insert_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583703312,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583743046,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/khugepaged.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:alloc_charge_hpage"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621964069,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:zswap_current_read",
        "mm/memcontrol.c:mem_cgroup_get_nr_swap_pages",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_replace_folio",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_swapin_charge_folio",
        "mm/memcontrol.c:mem_cgroup_hugetlb_try_charge",
        "mm/memcontrol.c:mem_cgroup_calculate_protection",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:memory_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_wb_stats",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:memcg_numa_stat_show",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:split_page_memcg",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:drain_obj_stock",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mod_objcg_state",
        "mm/memcontrol.c:mem_cgroup_from_slab_obj",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:folio_lruvec_lock_irqsave",
        "mm/memcontrol.c:folio_lruvec_lock_irq",
        "mm/memcontrol.c:folio_lruvec_lock",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_current",
        "mm/memcontrol.c:get_mem_cgroup_from_mm",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_kmem_state",
        "mm/memcontrol.c:__lruvec_stat_mod_folio",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583830149,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/vmpressure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583832629,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/swap_cgroup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/swap_cgroup.c:swap_cgroup_swapoff",
        "mm/swap_cgroup.c:swap_cgroup_swapon"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583844880,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-failure.c:delete_from_lru_cache"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583893696,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/userfaultfd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/userfaultfd.c:mfill_atomic_copy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583912061,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/memremap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memremap.c:free_zone_device_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509749,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "fs/dax.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/dax.c:dax_iomap_pte_fault"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492459836,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492480536,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492498812,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492572032,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492596024,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492711400,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492753724,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492816164,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493065640,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510979384,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493867840,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226335672,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 3226354772,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 3226365860,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 3226434624,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 3226450576,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226547888,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 3226582152,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3226624540,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 3226775976,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 3243459204,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285738772,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285765656,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285782664,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285881216,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285909760,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286048988,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286113448,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286197736,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286506808,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302636868,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055287497980,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272531570,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272546576,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272556474,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272614072,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272627818,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272709632,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272734972,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272775646,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272929896,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270701980,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:__memcg_kmem_charge",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936273432352,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581064110,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581081736,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581093052,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581159721,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581178418,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581272153,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581316774,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581384998,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581588791,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604844832,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582260817,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011320,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028920,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581040222,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581106585,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581125218,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581218777,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581260934,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327766,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581530311,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604813893,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582197769,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581055310,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581072936,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581084252,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581150921,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581169618,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581263353,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581307974,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581376198,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581580103,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604922016,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582251297,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
  "name": "mem_cgroup_disabled",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581116837,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:filemap_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581134600,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/oom_kill.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/oom_kill.c:__oom_kill_process"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581146172,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581213657,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:snapshot_refaults",
        "mm/vmscan.c:shrink_node_memcg",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:get_scan_count",
        "mm/vmscan.c:inactive_list_is_low",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:lruvec_lru_size",
        "mm/vmscan.c:lruvec_lru_size"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581232403,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/shmem.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/shmem.c:shmem_swapin_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581327209,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:count_shadow_nodes",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_activation",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_eviction",
        "mm/workingset.c:workingset_eviction"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581371974,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:do_swap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581440054,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581645356,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:alloc_slab_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604943543,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_swap_init",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_migrate",
        "mm/memcontrol.c:mem_cgroup_uncharge_list",
        "mm/memcontrol.c:mem_cgroup_uncharge",
        "mm/memcontrol.c:mem_cgroup_cancel_charge",
        "mm/memcontrol.c:mem_cgroup_commit_charge",
        "mm/memcontrol.c:mem_cgroup_try_charge",
        "mm/memcontrol.c:mem_cgroup_protected",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:get_mctgt_type",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_css_alloc",
        "mm/memcontrol.c:mem_cgroup_swappiness_read",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_node_nr_lru_pages",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_from_obj",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_get_max",
        "mm/memcontrol.c:mem_cgroup_update_lru_size",
        "mm/memcontrol.c:mem_cgroup_page_lruvec",
        "mm/memcontrol.c:mem_cgroup_iter",
        "mm/memcontrol.c:get_mem_cgroup_from_page",
        "mm/memcontrol.c:__count_memcg_events",
        "mm/memcontrol.c:__mod_lruvec_slab_state",
        "mm/memcontrol.c:__mod_lruvec_state",
        "mm/memcontrol.c:__mod_memcg_state"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582331629,
      "name": "mem_cgroup_disabled",
      "external": false,
      "loc": "include/linux/memcontrol.h:354",
      "file": "fs/dax.c",
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool mem_cgroup_disabled()
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool mem_cgroup_disabled()
```
</details>
</li>
</ul>
