# Function: <code>adjust_managed_page_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489552,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:5779",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_retrieve",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/balloon.c:free_xenballooned_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489552,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580573552,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:6406",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:free_xenballooned_pages",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580573552,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639984,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:6445",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639984,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580672448,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:6740",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672448,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580757856,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:6753",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580757856,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897088,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:6921",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897088,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580968624,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7228",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:generic_online_page",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580968624,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581386336,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7430",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581386336,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581447280,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581447280,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581652496,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7489",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/balloon.c:increase_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581652496,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581700080,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7635",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:decrease_reservation",
        "drivers/xen/balloon.c:increase_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581700080,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721792,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7853",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/memory_hotplug.c:offline_pages",
        "mm/memory_hotplug.c:put_page_bootmem",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721792,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581993984,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:8095",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/memory_hotplug.c:offline_pages",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/bootmem_info.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993984,
      "name": "adjust_managed_page_count",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582417072,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:8281",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/memory_hotplug.c:offline_pages",
        "mm/hugetlb.c:hugetlb_init",
        "mm/bootmem_info.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582417072,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582925056,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:8455",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_shrink_memory",
        "mm/page_alloc.c:free_reserved_area",
        "mm/memory_hotplug.c:offline_pages",
        "mm/hugetlb.c:hugetlb_init",
        "mm/bootmem_info.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582925056,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583141456,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:5518",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:__crash_shrink_memory",
        "mm/page_alloc.c:free_reserved_area",
        "mm/memory_hotplug.c:offline_pages",
        "mm/hugetlb.c:hugetlb_init",
        "mm/bootmem_info.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583141456,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583324576,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:5660",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:__crash_shrink_memory",
        "mm/page_alloc.c:free_reserved_area",
        "mm/memory_hotplug.c:offline_pages",
        "mm/hugetlb.c:gather_bootmem_prealloc",
        "mm/bootmem_info.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/virtio/virtio_balloon.c:fill_balloon",
        "drivers/xen/balloon.c:balloon_thread",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583324576,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492857632,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492857632,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226656712,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226656712,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286279300,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock"
      ],
      "caller_func": [
        "arch/powerpc/kernel/crash_dump.c:crash_free_reserved_phys_range",
        "arch/powerpc/kernel/fadump.c:fadump_release_reserved_area",
        "arch/powerpc/kernel/fadump.c:fadump_setup_cpu_notes_buf",
        "arch/powerpc/mm/init_64.c:vmemmap_free",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286241808,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272824014,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_init",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272801438,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581416128,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581416128,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581358640,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581358640,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581407328,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407328,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
void adjust_managed_page_count(struct page * page, long int count)
```

```json
{
  "name": "adjust_managed_page_count",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581471424,
      "name": "adjust_managed_page_count",
      "external": true,
      "loc": "mm/page_alloc.c:7460",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:free_pagetable",
        "kernel/kexec_core.c:crash_free_reserved_phys_range",
        "mm/page_alloc.c:free_reserved_area",
        "mm/page_alloc.c:init_cma_reserved_pageblock",
        "mm/hugetlb.c:hugetlb_init",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory_hotplug.c:__online_page_increment_counters",
        "mm/memory_hotplug.c:put_page_bootmem",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:virtballoon_migratepage",
        "drivers/virtio/virtio_balloon.c:leak_balloon",
        "drivers/xen/balloon.c:balloon_process",
        "drivers/xen/balloon.c:decrease_reservation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471424,
      "name": "adjust_managed_page_count",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
