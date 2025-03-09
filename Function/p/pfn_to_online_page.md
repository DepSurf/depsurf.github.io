# Function: <code>pfn_to_online_page</code>

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
struct page * pfn_to_online_page(long unsigned int pfn)
```

```json
{
  "name": "pfn_to_online_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581754256,
      "name": "pfn_to_online_page",
      "external": true,
      "loc": "mm/memory_hotplug.c:307",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:shrink_zone_span",
        "mm/memory_hotplug.c:shrink_zone_span",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_idle.c:page_idle_get_page",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581754256,
      "name": "pfn_to_online_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct page * pfn_to_online_page(long unsigned int pfn)
```

```json
{
  "name": "pfn_to_online_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582035584,
      "name": "pfn_to_online_page",
      "external": true,
      "loc": "mm/memory_hotplug.c:256",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:zone_for_pfn_range",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_idle.c:page_idle_get_page",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582035584,
      "name": "pfn_to_online_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct page * pfn_to_online_page(long unsigned int pfn)
```

```json
{
  "name": "pfn_to_online_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582467376,
      "name": "pfn_to_online_page",
      "external": true,
      "loc": "mm/memory_hotplug.c:272",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:zone_for_pfn_range",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_idle.c:page_idle_get_page",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582467376,
      "name": "pfn_to_online_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
struct page * pfn_to_online_page(long unsigned int pfn)
```

```json
{
  "name": "pfn_to_online_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979712,
      "name": "pfn_to_online_page",
      "external": true,
      "loc": "mm/memory_hotplug.c:259",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:zone_for_pfn_range",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_idle.c:page_idle_get_page",
        "fs/proc/kcore.c:read_kcore",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979712,
      "name": "pfn_to_online_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
struct page * pfn_to_online_page(long unsigned int pfn)
```

```json
{
  "name": "pfn_to_online_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583191488,
      "name": "pfn_to_online_page",
      "external": true,
      "loc": "mm/memory_hotplug.c:258",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/snapshot.c:saveable_page",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:zone_for_pfn_range",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_idle.c:page_idle_get_folio",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191488,
      "name": "pfn_to_online_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
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
struct page * pfn_to_online_page(long unsigned int pfn)
```

```json
{
  "name": "pfn_to_online_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583376384,
      "name": "pfn_to_online_page",
      "external": true,
      "loc": "mm/memory_hotplug.c:326",
      "file": "mm/memory_hotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mce_panic",
        "kernel/power/snapshot.c:saveable_page",
        "mm/vmstat.c:pagetypeinfo_showblockcount_print",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/compaction.c:__reset_isolation_pfn",
        "mm/page_alloc.c:alloc_contig_pages",
        "mm/page_alloc.c:__pageblock_pfn_to_page",
        "mm/memory_hotplug.c:try_offline_memory_block",
        "mm/memory_hotplug.c:zone_for_pfn_range",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/memory_hotplug.c:remove_pfn_range_from_zone",
        "mm/huge_memory.c:split_huge_pages_all",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:test_pages_isolated",
        "mm/page_isolation.c:undo_isolate_page_range",
        "mm/page_isolation.c:start_isolate_page_range",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_isolation.c:isolate_single_pageblock",
        "mm/page_idle.c:page_idle_get_folio",
        "fs/proc/kcore.c:read_kcore_iter",
        "fs/proc/page.c:kpagecgroup_read",
        "fs/proc/page.c:kpageflags_read",
        "fs/proc/page.c:kpagecount_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583376384,
      "name": "pfn_to_online_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct page * pfn_to_online_page(long unsigned int pfn)
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
