# Function: <code>walk_system_ram_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579397856,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:453",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579397856,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410176,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:479",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410176,
      "name": "walk_system_ram_range",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579430480,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:479",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579430480,
      "name": "walk_system_ram_range",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418128,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:479",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/ioremap.c:__ioremap_caller",
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418128,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446096,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:496",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446096,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460976,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:464",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460976,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494528,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:458",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494528,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512528,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512528,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538704,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538704,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569207,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579570432,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550615,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:482",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551840,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579554311,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:465",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556432,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626871,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:465",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629008,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579722804,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:452",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579724256,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579849892,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:452",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853824,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900132,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:452",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904080,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579938868,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:507",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:page_is_ram"
      ],
      "caller_func": [
        "arch/x86/mm/pat/memtype.c:pat_pagerange_is_ram",
        "kernel/dma/direct.c:dma_direct_all_ram_mapped",
        "mm/memory_hotplug.c:offline_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943296,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490685168,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490685168,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224754468,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224754468,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283509744,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/iommu.c:enable_ddw",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283509744,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271419014,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:page_is_ram",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271419014,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512368,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512368,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441168,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441168,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579512288,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579512288,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int walk_system_ram_range(long unsigned int start_pfn, long unsigned int nr_pages, void * arg, int (*)(long unsigned int, long unsigned int, void *) func)
```

```json
{
  "name": "walk_system_ram_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579545216,
      "name": "walk_system_ram_range",
      "external": true,
      "loc": "kernel/resource.c:475",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pat.c:pat_pagerange_is_ram",
        "kernel/resource.c:page_is_ram",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:online_pages",
        "fs/proc/kcore.c:kcore_update_ram"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579545216,
      "name": "walk_system_ram_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
