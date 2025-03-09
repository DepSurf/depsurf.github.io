# Function: <code>node_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595069009,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580978338,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    },
    {
      "addr": 18446744071580604674,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpuup_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587338840,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:403",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580978338,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595234684,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:numa_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581133201,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ]
    },
    {
      "addr": 18446744071580707661,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpuup_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587841472,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581133201,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581001088,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595475787,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208285,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    },
    {
      "addr": 18446744071580773393,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": [
        "mm/vmstat.c:setup_vmstat"
      ]
    },
    {
      "addr": 18446744071588056275,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:412",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581208285,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580772160,
      "name": "node_set_state.constprop.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071581074880,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596397410,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:408",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580702065,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:408",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    },
    {
      "addr": 18446744071580809841,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:408",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071588283069,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:408",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580702065,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580808016,
      "name": "node_set_state.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071581123168,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602717089,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580787489,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    },
    {
      "addr": 18446744071580899457,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071588848221,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580787489,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071580897216,
      "name": "node_set_state.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071581235760,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602889788,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580920858,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes"
      ]
    },
    {
      "addr": 18446744071581035265,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071589227286,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580920858,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581033104,
      "name": "node_set_state.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604687146,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580996702,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ]
    },
    {
      "addr": 18446744071581112849,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071589470270,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580996702,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581110672,
      "name": "node_set_state.constprop.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604786864,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604872203,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604890141,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589928397,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604812602,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604906109,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604924078,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590155613,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609150527,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609224370,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609238167,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591173249,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:node_states_set_node",
        "mm/memory_hotplug.c:node_states_set_node",
        "mm/memory_hotplug.c:node_states_set_node"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612220862,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612291466,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612304562,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591669019,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612404169,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614361917,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614431113,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614444863,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591613330,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614546617,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615293081,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615371035,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615387478,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592786943,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615498803,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:419",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
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
void node_set_state(int node, enum node_states state)
```

```json
{
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593859215,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:node_set_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582127881,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": [
        "mm/vmstat.c:init_mm_internals"
      ]
    },
    {
      "addr": 18446744071593979422,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ]
    },
    {
      "addr": 18446744071594685678,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617301885,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593968676,
      "name": "node_set_state.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071593979422,
      "name": "node_set_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627729170,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627843787,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071627868226,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:free_area_init",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596422238,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628019996,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619488370,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:alloc_node_data",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619608283,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619618212,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596962366,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619785452,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621784722,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_gi_nodes",
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621912459,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071621922469,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/mm_init.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:free_area_init",
        "mm/mm_init.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597890041,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:__try_online_node",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622092677,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:426",
      "file": "drivers/acpi/numa/srat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/numa/srat.c:acpi_parse_gi_affinity"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490361632,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/arm64/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:node_set_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510944428,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510962812,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503906656,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:469",
      "file": "mm/vmstat.c",
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055282833920,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/powerpc/mm/numa.c:node_set_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302592712,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302615948,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286555320,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:469",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:469",
      "file": "mm/page_alloc.c",
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604726544,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604811569,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604829538,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589757901,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604694274,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604780630,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604798599,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589482125,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604804111,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604888753,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604906722,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590201309,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
  "name": "node_set_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604816730,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "arch/x86/mm/numa.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:alloc_node_data"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604910290,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:init_mm_internals",
        "mm/vmstat.c:vmstat_cpu_online"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604928259,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/page_alloc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:free_area_init_nodes",
        "mm/page_alloc.c:find_zone_movable_pfns_for_nodes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590251709,
      "name": "node_set_state",
      "external": false,
      "loc": "include/linux/nodemask.h:418",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:add_memory_resource",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void node_set_state(int node, enum node_states state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void node_set_state(int node, enum node_states state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void node_set_state(int node, enum node_states state)
```
</details>
</li>
</ul>
