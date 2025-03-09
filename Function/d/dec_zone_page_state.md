# Function: <code>dec_zone_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580599440,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:377",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/memory.c:__pte_alloc",
        "mm/migrate.c:putback_movable_pages",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:khugepaged",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580599440,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701248,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:455",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701248,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767056,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:455",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:handle_mm_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767056,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803536,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:455",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803536,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892256,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:530",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892256,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028432,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:530",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:handle_pte_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028432,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581105968,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:530",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:__handle_mm_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581105968,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170592,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_shmem",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170592,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228624,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228624,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581422112,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:retract_page_tables",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581422112,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465264,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:540",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465264,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486064,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:546",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486064,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581741664,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:592",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581741664,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582123328,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:621",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swap.c:release_pages",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582123328,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597632,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:608",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597632,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582805568,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:609",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582805568,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979840,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:609",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:alloc_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979840,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492627152,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492627152,
      "name": "dec_zone_page_state",
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226477300,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:625",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/mm/pgd.c:pgd_free",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226477300,
      "name": "dec_zone_page_state",
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285948448,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:625",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/mm/pgtable-frag.c:pte_fragment_free",
        "arch/powerpc/mm/pgtable-frag.c:pte_frag_destroy",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285948448,
      "name": "dec_zone_page_state",
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272651386,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:625",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/memory.c:free_pgd_range",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272651386,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197472,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197472,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144224,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144224,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188672,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188672,
      "name": "dec_zone_page_state",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void dec_zone_page_state(struct page * page, enum zone_stat_item item)
```

```json
{
  "name": "dec_zone_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252000,
      "name": "dec_zone_page_state",
      "external": true,
      "loc": "mm/vmstat.c:531",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/pgtable.c:___pte_free_tlb",
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/memory.c:do_fault",
        "mm/memory.c:__pte_alloc",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/huge_memory.c:do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/zsmalloc.c:zs_page_migrate",
        "mm/zsmalloc.c:zs_malloc",
        "mm/zsmalloc.c:__free_zspage",
        "block/bounce.c:bounce_end_io"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252000,
      "name": "dec_zone_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
