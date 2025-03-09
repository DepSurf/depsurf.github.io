# Function: <code>__node_distance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322992,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:429",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_domains_numa_masks_update",
        "kernel/sched/core.c:find_numa_distance",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_fault",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/huge_memory.c:khugepaged",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322992,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595232852,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:428",
      "file": "arch/x86/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/numa.c:init_cpu_to_node"
      ],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:find_numa_distance",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328624,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579343968,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:428",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_init_smp",
        "kernel/sched/core.c:sched_cpu_activate",
        "kernel/sched/core.c:find_numa_distance",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343968,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338000,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:428",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338000,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363408,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:428",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363408,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376016,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:428",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376016,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403680,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:427",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:task_numa_fault",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403680,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419104,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:424",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419104,
      "name": "__node_distance",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422272,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:424",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422272,
      "name": "__node_distance",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452384,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:439",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452384,
      "name": "__node_distance",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579449312,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:437",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449312,
      "name": "__node_distance",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579451808,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:443",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:find_numa_distance",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579451808,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579516880,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:442",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:init_numa_topology_type",
        "kernel/sched/topology.c:find_numa_distance",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516880,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600624,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:442",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:find_numa_distance",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/migrate.c:__set_migration_target_nodes",
        "mm/khugepaged.c:khugepaged_scan_abort",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600624,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579713328,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:442",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:find_numa_distance",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/khugepaged.c:hpage_collapse_scan_abort",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713328,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579726608,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:442",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:find_numa_distance",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/khugepaged.c:hpage_collapse_scan_abort",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579726608,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579761552,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:444",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:can_migrate_task",
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/build_utility.c:sched_domains_numa_masks_set",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:sched_init_numa",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:init_numa_topology_type",
        "kernel/sched/build_utility.c:find_numa_distance",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:find_next_best_node",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "mm/memory-tiers.c:establish_demotion_targets",
        "mm/khugepaged.c:hpage_collapse_scan_abort",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761552,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336510834816,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/arm64/mm/numa.c:339",
      "file": "arch/arm64/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/mm/numa.c:pcpu_cpu_distance"
      ],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490360952,
      "name": "__node_distance",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int __node_distance(int a, int b)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055282824800,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/powerpc/mm/numa.c:188",
      "file": "arch/powerpc/mm/numa.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:task_numa_placement",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282824800,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418112,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:424",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvme/host/multipath.c:__nvme_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418112,
      "name": "__node_distance",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579347248,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:424",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance",
        "drivers/nvme/host/multipath.c:__nvme_find_path"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347248,
      "name": "__node_distance",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418032,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:424",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418032,
      "name": "__node_distance",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __node_distance(int from, int to)
```

```json
{
  "name": "__node_distance",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579427088,
      "name": "__node_distance",
      "external": true,
      "loc": "arch/x86/mm/numa.c:424",
      "file": "arch/x86/mm/numa.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/fair.c:preferred_group_nid",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/fair.c:task_numa_migrate",
        "kernel/sched/topology.c:sched_domains_numa_masks_set",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "kernel/sched/topology.c:sched_init_numa",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:build_zonelists",
        "mm/page_alloc.c:get_page_from_freelist",
        "mm/sparse-vmemmap.c:vmemmap_verify",
        "drivers/acpi/numa.c:acpi_map_pxm_to_online_node",
        "drivers/base/node.c:node_read_distance"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579427088,
      "name": "__node_distance",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __node_distance(int from, int to)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int a</code>
</li>
<li>
<b>Param added. </b>
<code>int b</code>
</li>
<li>
<b>Param removed. </b>
<code>int from</code>
</li>
<li>
<b>Param removed. </b>
<code>int to</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __node_distance(int from, int to)
```
</details>
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
