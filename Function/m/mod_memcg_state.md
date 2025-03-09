# Function: <code>mod_memcg_state</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579374306,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:513",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580710522,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:513",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580869980,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:513",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581099679,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:513",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401170,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:516",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580796073,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:516",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580960940,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:516",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581210348,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:516",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579414338,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:554",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492933,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:554",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448847,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578805,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:594",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468724,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:590",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581689977,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:590",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579494794,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581763401,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579517939,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:603",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:memcg_charge_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581982743,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:603",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581488321,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:921",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_memcg_free_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582033063,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:921",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581508129,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:966",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_memcg_free_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582059847,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:966",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581767110,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:957",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582367777,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:957",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
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
void mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582146624,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:954",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ]
    },
    {
      "addr": 18446744071582385408,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:954",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vunmap"
      ]
    },
    {
      "addr": 18446744071582838960,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:954",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582146624,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582385408,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071582838960,
      "name": "mod_memcg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582625296,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:962",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ]
    },
    {
      "addr": 18446744071582892240,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:962",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:__vunmap"
      ]
    },
    {
      "addr": 18446744071583384272,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:962",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582625296,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071582892240,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583384272,
      "name": "mod_memcg_state",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582834384,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:978",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_memcg_post_alloc_hook"
      ]
    },
    {
      "addr": 18446744071583107824,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:978",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node",
        "mm/vmalloc.c:vfree"
      ]
    },
    {
      "addr": 18446744071583604896,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:978",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582834384,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583107824,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583604896,
      "name": "mod_memcg_state",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583008832,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:997",
      "file": "mm/percpu.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583290448,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:997",
      "file": "mm/vmalloc.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmalloc.c:__vmalloc_area_node"
      ]
    },
    {
      "addr": 18446744071583799504,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:997",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_uncharge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:obj_cgroup_charge_zswap",
        "mm/memcontrol.c:__mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:__mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583008832,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583290448,
      "name": "mod_memcg_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071583799504,
      "name": "mod_memcg_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490627244,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:dup_task_struct"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493217348,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226848612,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286731056,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272993562,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468458,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581732137,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579397380,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581670809,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579468378,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581723449,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
  "name": "mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579500113,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581791666,
      "name": "mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:626",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state"
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
void mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
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
