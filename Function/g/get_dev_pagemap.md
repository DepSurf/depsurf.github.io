# Function: <code>get_dev_pagemap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579309500,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580765204,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581026699,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
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
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579324713,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "arch/x86/mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/gup.c:gup_huge_pmd",
        "arch/x86/mm/gup.c:gup_pte_range"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580830788,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/gup.c:follow_page_pte"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581101850,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pmd"
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
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580880029,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
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
      "addr": 18446744071581151881,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:84",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
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
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580964850,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:184",
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
      "addr": 18446744071581273029,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:184",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580849744,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "kernel/memremap.c:297",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/gup.c:gup_pgd_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580849744,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917744,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "kernel/memremap.c:288",
      "file": "kernel/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917744,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738080,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:365",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738080,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581811600,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:387",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811600,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031936,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:420",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031936,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582080240,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:469",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582080240,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582105312,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:475",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "drivers/dax/super.c:__generic_fsdax_supported",
        "drivers/dax/super.c:__generic_fsdax_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582105312,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582421440,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:472",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "drivers/dax/super.c:generic_fsdax_supported",
        "drivers/dax/super.c:generic_fsdax_supported"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582421440,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582937040,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:430",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582937040,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583493168,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:446",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583493168,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708144,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:446",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708144,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583908496,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:434",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:gup_pte_range",
        "mm/gup.c:follow_page_pte",
        "mm/memory_hotplug.c:pfn_to_online_page",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583908496,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/huge_memory.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/memory-failure.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "drivers/dax/super.c",
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
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "drivers/dax/super.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286807056,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:387",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286807056,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "mm/hmm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "get_dev_pagemap",
      "external": false,
      "loc": "include/linux/memremap.h:153",
      "file": "drivers/dax/super.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581780336,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:387",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780336,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581718496,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:387",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581718496,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581771648,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:387",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581771648,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```

```json
{
  "name": "get_dev_pagemap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581840512,
      "name": "get_dev_pagemap",
      "external": true,
      "loc": "mm/memremap.c:387",
      "file": "mm/memremap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:gup_pud_range",
        "mm/gup.c:__gup_device_huge",
        "mm/gup.c:follow_page_pte",
        "mm/huge_memory.c:follow_devmap_pud",
        "mm/huge_memory.c:follow_devmap_pmd",
        "mm/memory-failure.c:memory_failure",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/hmm.c:hmm_vma_walk_pud",
        "mm/hmm.c:hmm_vma_walk_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581840512,
      "name": "get_dev_pagemap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct dev_pagemap * get_dev_pagemap(long unsigned int pfn, struct dev_pagemap * pgmap)
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
