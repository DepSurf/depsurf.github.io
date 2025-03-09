# Function: <code>__remove_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873536,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:765",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873536,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1333
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
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581001232,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:825",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581001232,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1390
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
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075024,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:811",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075024,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1364
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
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581125280,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:565",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581125280,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1351
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
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581237968,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:574",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/hmm.c:hmm_devmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581237968,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1388
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:553",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/hmm.c:hmm_devmem_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386802,
      "name": "__remove_pages.cold.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581383936,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int __remove_pages(struct zone * zone, long unsigned int phys_start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:553",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "kernel/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471073,
      "name": "__remove_pages.cold.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581468160,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1296
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
void __remove_pages(struct zone * zone, long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581583680,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:541",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581583680,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1490
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581648352,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581648352,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581865600,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:534",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865600,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581910480,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:534",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:pageunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581910480,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581757040,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:576",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581757040,
      "name": "__remove_pages",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582038208,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:519",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582038208,
      "name": "__remove_pages",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468256,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:530",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468256,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582982608,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:518",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982608,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583194256,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:505",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583194256,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583379152,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:573",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379152,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493097384,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:arch_remove_memory"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493097384,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286548704,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/mem.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286548704,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617088,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617088,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581558416,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581558416,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581608400,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581608400,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "__remove_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581674592,
      "name": "__remove_pages",
      "external": true,
      "loc": "mm/memory_hotplug.c:520",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:arch_remove_memory",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581674592,
      "name": "__remove_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap * altmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int phys_start_pfn</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct zone * zone</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, pfn, nr_pages, altmap</code> ➡️ <code>pfn, nr_pages, altmap</code>
</li>
</ul>
</details>
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
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
void __remove_pages(long unsigned int pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
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
