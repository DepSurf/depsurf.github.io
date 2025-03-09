# Function: <code>memmap_init_range</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "memmap_init_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591626852,
      "name": "memmap_init_range",
      "external": true,
      "loc": "mm/page_alloc.c:6317",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591626852,
      "name": "memmap_init_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "memmap_init_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592800397,
      "name": "memmap_init_range",
      "external": true,
      "loc": "mm/page_alloc.c:6501",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592800397,
      "name": "memmap_init_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "memmap_init_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594700683,
      "name": "memmap_init_range",
      "external": true,
      "loc": "mm/page_alloc.c:6563",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594700683,
      "name": "memmap_init_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 555
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
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "memmap_init_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596441648,
      "name": "memmap_init_range",
      "external": true,
      "loc": "mm/page_alloc.c:6730",
      "file": "mm/page_alloc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:memmap_init",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596441648,
      "name": "memmap_init_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 748
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
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "memmap_init_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596982032,
      "name": "memmap_init_range",
      "external": true,
      "loc": "mm/mm_init.c:838",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memmap_init",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596982032,
      "name": "memmap_init_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 692
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
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```

```json
{
  "name": "memmap_init_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597910688,
      "name": "memmap_init_range",
      "external": true,
      "loc": "mm/mm_init.c:849",
      "file": "mm/mm_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mm_init.c:memmap_init",
        "mm/memory_hotplug.c:move_pfn_range_to_zone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597910688,
      "name": "memmap_init_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void memmap_init_range(long unsigned int size, int nid, long unsigned int zone, long unsigned int start_pfn, long unsigned int zone_end_pfn, enum meminit_context context, struct vmem_altmap * altmap, int migratetype)
```
</details>
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
