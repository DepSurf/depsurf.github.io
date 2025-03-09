# Function: <code>inc_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580603808,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:371",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/vmscan.c:shrink_page_list",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/mempolicy.c:queue_pages_pte_range",
        "mm/migrate.c:SyS_move_pages",
        "mm/huge_memory.c:khugepaged",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepage_locked",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580603808,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706384,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:449",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706384,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772320,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:449",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772320,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580808768,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:449",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/mempolicy.c:alloc_page_interleave",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580808768,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897952,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:524",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897952,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033856,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:524",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033856,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581111424,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:524",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111424,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581176128,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581176128,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581234256,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581234256,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421936,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421936,
      "name": "inc_zone_page_state",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465088,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:534",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465088,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485888,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:540",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485888,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741408,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:586",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741408,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123040,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:615",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123040,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597952,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:602",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597952,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805264,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:603",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805264,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980144,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:603",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980144,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492627512,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/mm/mmu.c:pgd_pgtable_alloc",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492627512,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 356
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226476724,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:613",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/mmu.c:late_alloc",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226476724,
      "name": "inc_zone_page_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285947680,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:613",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_alloc",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285947680,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272650686,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:613",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/memory.c:do_fault",
        "mm/memory.c:__do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272650686,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581203104,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581203104,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581149856,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581149856,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581194304,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581194304,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void inc_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "inc_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581257584,
      "name": "inc_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:525",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:pte_alloc_one",
        "mm/page-writeback.c:__test_set_page_writeback",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "block/bounce.c:__blk_queue_bounce"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581257584,
      "name": "inc_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
