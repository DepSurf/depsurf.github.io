# Function: <code>__node_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579358651,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:122",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579611336,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:122",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580604601,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:122",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpuup_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580816780,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:122",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580873408,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:122",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580939203,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:122",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358651,
      "name": "__node_clear.constprop.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071580873408,
      "name": "__node_clear",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579365536,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579624751,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_fault"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580707589,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpuup_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580942195,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003593,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581086013,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365536,
      "name": "__node_clear.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581001072,
      "name": "__node_clear",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579383638,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579622614,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580773484,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581014882,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077581,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581160965,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383638,
      "name": "__node_clear.constprop.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581074864,
      "name": "__node_clear",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579291328,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579602002,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580809932,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581055499,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581124884,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581208608,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:124",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291328,
      "name": "__node_clear.constprop.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581123152,
      "name": "__node_clear",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579311071,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579634354,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580899548,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581166859,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581237576,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ]
    },
    {
      "addr": 18446744071581338976,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579311071,
      "name": "__node_clear.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581235744,
      "name": "__node_clear",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322581,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579656387,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035356,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581310156,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581383292,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ]
    },
    {
      "addr": 18446744071581486466,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322581,
      "name": "__node_clear.constprop.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581381888,
      "name": "__node_clear",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void __node_clear(int node, volatile nodemask_t * dstp)
```

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346920,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ]
    },
    {
      "addr": 18446744071579698835,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581112940,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581392092,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581466805,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages"
      ]
    },
    {
      "addr": 18446744071581572242,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579346920,
      "name": "__node_clear.constprop.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071581466000,
      "name": "__node_clear",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604782451,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579731393,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581177612,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581504306,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589930029,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581683535,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604808218,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579774657,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581235724,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581538297,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581568706,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581646048,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755967,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609146935,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579812896,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581424630,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581747545,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581782033,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581861344,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:node_states_clear_node",
        "mm/memory_hotplug.c:node_states_clear_node",
        "mm/memory_hotplug.c:node_states_clear_node",
        "mm/memory_hotplug.c:new_node_page"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612217272,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579803440,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581467862,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581795833,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581833376,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581908416,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:node_states_clear_node",
        "mm/memory_hotplug.c:node_states_clear_node",
        "mm/memory_hotplug.c:node_states_clear_node"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614358504,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579809821,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581488598,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581755192,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581822581,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581864230,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581935885,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_memory_callback"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615288950,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579906973,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581745034,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582036382,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582108997,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582155766,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582229333,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_memory_callback"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617068293,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580019332,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128053,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582465071,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582550029,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582610911,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582695615,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_memory_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582716343,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/migrate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/migrate.c:__set_migration_target_nodes"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627716926,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580188225,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582603205,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582978936,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583072971,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583134135,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583214175,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_memory_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596458279,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memtier_hotplug_callback"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619474398,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580253410,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582811109,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583190712,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583281627,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583344457,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583432398,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_memory_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596999639,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memtier_hotplug_callback"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621770878,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580303154,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582985685,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583375608,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:do_migrate_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583421038,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:slab_memory_callback"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583518664,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583580563,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:do_migrate_pages"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597928983,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:135",
      "file": "mm/memory-tiers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory-tiers.c:memtier_hotplug_callback"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490974600,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492629768,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492971324,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336493004500,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493209408,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283817976,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:task_numa_placement"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285947056,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286389240,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286433388,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055286543784,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055286718604,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
  "name": "__node_clear",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272877802,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604722160,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579750513,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581204572,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581507033,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581537442,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581614784,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581724703,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604690062,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579680897,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581151324,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581449225,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581479202,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581556112,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581663503,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604799727,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579735025,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581195772,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581498345,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581528754,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581606096,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581716015,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
  "name": "__node_clear",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604812346,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:paging_init",
        "arch/x86/mm/init_64.c:paging_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579782689,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "kernel/sched/fair.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/sched/fair.c:preferred_group_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581259052,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/vmstat.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmstat.c:vmstat_cpu_dead"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581565311,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/hugetlb.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/hugetlb.c:alloc_fresh_huge_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581595442,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/mempolicy.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581672288,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:new_node_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581783583,
      "name": "__node_clear",
      "external": false,
      "loc": "include/linux/nodemask.h:134",
      "file": "mm/memcontrol.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memcontrol.c:mem_cgroup_select_victim_node"
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
void __node_clear(int node, volatile nodemask_t * dstp)
```
</details>
</li>
</ul>
