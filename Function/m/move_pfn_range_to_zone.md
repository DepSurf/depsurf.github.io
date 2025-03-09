# Function: <code>move_pfn_range_to_zone</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588279392,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:823",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588279392,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588844896,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:807",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588844896,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589223984,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:783",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:online_pages",
        "mm/hmm.c:hmm_devmem_pages_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589223984,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589466560,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:742",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589466560,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589927024,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:721",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:devm_memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589927024,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 337
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590154256,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590154256,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591171888,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:698",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591171888,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591667504,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:692",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591667504,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591611664,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:749",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_init_memmap_on_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591611664,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592785456,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:692",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_init_memmap_on_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592785456,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594684160,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:691",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_init_memmap_on_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594684160,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 377
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596420560,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:687",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_init_memmap_on_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596420560,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 499
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596960624,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:681",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_init_memmap_on_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596960624,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597888256,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:750",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memory_hotplug.c:mhp_init_memmap_on_memory",
        "mm/memremap.c:pagemap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597888256,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 514
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503905320,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503905320,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 520
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286553296,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286553296,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589756544,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589756544,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480768,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480768,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590199952,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590199952,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 339
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
```

```json
{
  "name": "move_pfn_range_to_zone",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590250352,
      "name": "move_pfn_range_to_zone",
      "external": true,
      "loc": "mm/memory_hotplug.c:704",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory_hotplug.c:online_pages",
        "mm/memremap.c:memremap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590250352,
      "name": "move_pfn_range_to_zone",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages)
```
</details>
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
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int migratetype</code>
</li>
</ul>
</details>
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
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
void move_pfn_range_to_zone(struct zone * zone, long unsigned int start_pfn, long unsigned int nr_pages, struct vmem_altmap * altmap)
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
