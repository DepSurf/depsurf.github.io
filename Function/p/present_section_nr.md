# Function: <code>present_section_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595148624,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1106",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:sparse_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595150010,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1106",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580875280,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1106",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:test_pages_in_a_zone",
        "mm/memory_hotplug.c:walk_memory_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584484574,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1106",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584486031,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1106",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:show_mem_removable",
        "drivers/base/memory.c:memory_dev_init"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595321057,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595321387,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581003379,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830505,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595466043,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:show_mem_removable"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595569322,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1156",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595569652,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1156",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581077357,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1156",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585023749,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1156",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:register_one_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595719055,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1156",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:show_mem_removable"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581070946,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:next_present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596497193,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581124648,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585108486,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:link_mem_sections"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596644182,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1178",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init",
        "drivers/base/memory.c:show_mem_removable"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581181988,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1191",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:next_present_section_nr"
      ]
    },
    {
      "addr": 18446744071602824526,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1191",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581237322,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1191",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585534681,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1191",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:link_mem_sections"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585537247,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1191",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:show_mem_removable"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581181988,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071585535280,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581326788,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1198",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:alloc_usemap_and_memmap",
        "mm/sparse.c:sparse_early_usemaps_alloc_node"
      ]
    },
    {
      "addr": 18446744071602997860,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1198",
      "file": "mm/sparse-vmemmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse-vmemmap.c:sparse_mem_maps_populate_node"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581383068,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1198",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:try_offline_node",
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585778355,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1198",
      "file": "drivers/base/node.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/node.c:link_mem_sections"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585781186,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1198",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:show_mem_removable"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326788,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585778928,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581410906,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1206",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581470684,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1206",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:walk_memory_range",
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585914221,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1206",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:removable_show"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581410906,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585911968,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581523288,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1274",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581586118,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1274",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586155632,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1274",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_block_action",
        "drivers/base/memory.c:removable_show"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581523288,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586153168,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581588055,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581649558,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586304205,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588055,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586301648,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581800202,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1258",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:next_present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581866643,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1258",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587075439,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1258",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_memory_block"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591332614,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1296",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:next_present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581911539,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1296",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612453642,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1296",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581758841,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1361",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071591275314,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1361",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:next_present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614595429,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1361",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582040832,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1398",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592216021,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1398",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:next_present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615552426,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1398",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_dev_init"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593994689,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1444",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:next_present_section_nr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617358701,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1444",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627888039,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1776",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628096645,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1776",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619651175,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1901",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619862565,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1901",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
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
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621958183,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1912",
      "file": "mm/sparse.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622171125,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1912",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:add_boot_memory_block"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493026328,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446603336499137408,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_block_action"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493026328,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336499135264,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286455644,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 13835058055286550412,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055292329816,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286455644,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 13835058055292325904,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272901222,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272901222,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581556791,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581618294,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586067453,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581556791,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586064896,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581498439,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581559622,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585913405,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498439,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585910848,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581548103,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581609606,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586252173,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581548103,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586249616,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int present_section_nr(long unsigned int nr)
```

```json
{
  "name": "present_section_nr",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581613223,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/sparse.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid",
        "mm/sparse.c:sparse_init_nid"
      ]
    },
    {
      "addr": 18446744071581675798,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "mm/memory_hotplug.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/memory_hotplug.c:test_pages_in_a_zone"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586363117,
      "name": "present_section_nr",
      "external": false,
      "loc": "include/linux/mmzone.h:1281",
      "file": "drivers/base/memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/memory.c:memory_subsys_online"
      ],
      "caller_func": [
        "drivers/base/memory.c:memory_dev_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613223,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586360560,
      "name": "present_section_nr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int present_section_nr(long unsigned int nr)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int present_section_nr(long unsigned int nr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int present_section_nr(long unsigned int nr)
```
</details>
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
