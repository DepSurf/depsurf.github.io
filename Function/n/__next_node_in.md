# Function: <code>__next_node_in</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583252144,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:5",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cpuset.c:cpuset_slab_spread_node",
        "kernel/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_zonelist",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583252144,
      "name": "__next_node_in",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367472,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:5",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cpuset.c:cpuset_slab_spread_node",
        "kernel/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_zonelist",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:mpol_rebind_nodemask",
        "mm/memory_hotplug.c:new_node_page",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/page_isolation.c:alloc_migrate_target"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367472,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588216544,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:5",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588216544,
      "name": "__next_node_in",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588766512,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:SYSC_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588766512,
      "name": "__next_node_in",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589145328,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589145328,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589380464,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589380464,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589837520,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589837520,
      "name": "__next_node_in",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590063664,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590063664,
      "name": "__next_node_in",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585060560,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585060560,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585209856,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585209856,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585092832,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page",
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:hstate_next_node_to_alloc",
        "mm/hugetlb.c:hstate_next_node_to_alloc",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585092832,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585540432,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page",
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:hstate_next_node_to_alloc",
        "mm/hugetlb.c:hstate_next_node_to_alloc",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540432,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 90
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
unsigned int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586695120,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page",
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/hugetlb.c:__alloc_bootmem_huge_page",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages_bulk_array_mempolicy",
        "mm/mempolicy.c:alloc_pages",
        "mm/mempolicy.c:vma_alloc_folio",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:do_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586695120,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
  "name": "__next_node_in",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579450279,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627728323,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581068487,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583083406,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583125889,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:do_get_mempolicy"
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
  "name": "__next_node_in",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579462455,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619487523,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581158845,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583294014,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_huge_page",
        "mm/hugetlb.c:alloc_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583336286,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:do_get_mempolicy"
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
  "name": "__next_node_in",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579492519,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621783843,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581264349,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583530702,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:demote_store",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:set_max_huge_pages",
        "mm/hugetlb.c:remove_pool_hugetlb_folio",
        "mm/hugetlb.c:alloc_pool_huge_folio",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/hugetlb.c:__alloc_bootmem_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583571892,
      "name": "__next_node_in",
      "external": false,
      "loc": "include/linux/nodemask.h:280",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:interleave_nodes",
        "mm/mempolicy.c:do_get_mempolicy"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503840912,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503840912,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236459988,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236459988,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297692288,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297692288,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279731684,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279731684,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589665920,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589665920,
      "name": "__next_node_in",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589391744,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589391744,
      "name": "__next_node_in",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590109296,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590109296,
      "name": "__next_node_in",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```

```json
{
  "name": "__next_node_in",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590159632,
      "name": "__next_node_in",
      "external": true,
      "loc": "lib/nodemask.c:6",
      "file": "lib/nodemask.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/numa.c:numa_init",
        "kernel/cgroup/cpuset.c:cpuset_slab_spread_node",
        "kernel/cgroup/cpuset.c:cpuset_mem_spread_node",
        "mm/hugetlb.c:__nr_hugepages_store_common",
        "mm/hugetlb.c:free_pool_huge_page",
        "mm/hugetlb.c:get_valid_node_allowed",
        "mm/mempolicy.c:alloc_pages_current",
        "mm/mempolicy.c:alloc_pages_vma",
        "mm/mempolicy.c:huge_node",
        "mm/mempolicy.c:mempolicy_slab_node",
        "mm/mempolicy.c:kernel_get_mempolicy",
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590159632,
      "name": "__next_node_in",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __next_node_in(int node, const nodemask_t * srcp)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int __next_node_in(int node, const nodemask_t * srcp)
```
</details>
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
