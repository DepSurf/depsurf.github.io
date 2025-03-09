# Function: <code>__mod_memcg_state</code>

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
  "name": "__mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580711386,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:506",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580958282,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:506",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580796954,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:508",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581060026,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:508",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
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
  "name": "__mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579414355,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:537",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:account_kernel_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580936077,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:537",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581095578,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:537",
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
      "addr": 18446744071581198687,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:537",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581356762,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:537",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581492950,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:537",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics"
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
  "name": "__mod_memcg_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448864,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "kernel/fork.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:account_kernel_stack"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003904,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/page-writeback.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_dirtied"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581174452,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/workingset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:shadow_lru_isolate",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault",
        "mm/workingset.c:workingset_refault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581282035,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581442060,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:__free_slab",
        "mm/slub.c:new_slab"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581578822,
      "name": "__mod_memcg_state",
      "external": false,
      "loc": "include/linux/memcontrol.h:577",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
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
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
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
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581672992,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "kernel/fork.c:account_kernel_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_move_account",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581672992,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581745248,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581745248,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581982760,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:682",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ],
      "caller_func": [
        "kernel/fork.c:memcg_charge_kernel_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581948912,
      "name": "__mod_memcg_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071581966832,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582033080,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:761",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995280,
      "name": "__mod_memcg_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
    },
    {
      "addr": 18446744071582015520,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582059864,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:640",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ],
      "caller_func": [
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:__mod_memcg_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020896,
      "name": "__mod_memcg_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446744071582041296,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582344144,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:697",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/percpu.c:pcpu_memcg_free_hook",
        "mm/percpu.c:pcpu_memcg_post_alloc_hook",
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
      "addr": 18446744071582344144,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582838784,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:671",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582838784,
      "name": "__mod_memcg_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583384048,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:741",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583384048,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583604640,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:766",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583604640,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583799104,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:817",
      "file": "mm/memcontrol.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mod_memcg_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799104,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 373
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493198160,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:dup_task_struct",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493198160,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226829628,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226829628,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286701776,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286701776,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272977528,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272977528,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713984,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713984,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652896,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652896,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581705296,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581705296,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```

```json
{
  "name": "__mod_memcg_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581772640,
      "name": "__mod_memcg_state",
      "external": true,
      "loc": "mm/memcontrol.c:691",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/fork.c:copy_process",
        "kernel/fork.c:copy_process",
        "kernel/fork.c:put_task_stack",
        "mm/memcontrol.c:mem_cgroup_uncharge_swap",
        "mm/memcontrol.c:mem_cgroup_try_charge_swap",
        "mm/memcontrol.c:mem_cgroup_swapout",
        "mm/memcontrol.c:mem_cgroup_uncharge_skmem",
        "mm/memcontrol.c:mem_cgroup_charge_skmem",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:uncharge_batch",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_move_charge_pte_range",
        "mm/memcontrol.c:mem_cgroup_split_huge_fixup",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mem_cgroup_charge_statistics",
        "mm/memcontrol.c:mod_memcg_obj_state",
        "mm/memcontrol.c:__mod_lruvec_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772640,
      "name": "__mod_memcg_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void __mod_memcg_state(struct mem_cgroup * memcg, int idx, int val)
```
</details>
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
