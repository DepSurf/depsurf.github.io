# Function: <code>migrate_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885696,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1122",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/migrate.c:SyS_move_pages",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885696,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2008
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014880,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1302",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SyS_move_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014880,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3024
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581089088,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1311",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089088,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3025
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581136480,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1299",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581136480,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2514
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581258128,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1378",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258128,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2873
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581404272,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1370",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581404272,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2818
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581487744,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1403",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581487744,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2845
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595888,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1398",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595888,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2966
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581666448,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581666448,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2966
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581887968,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1416",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581887968,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 629
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933872,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1423",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933872,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1176
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959296,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1403",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959296,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1258
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason, unsigned int * ret_succeeded)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582264112,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1442",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582264112,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1246
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason, unsigned int * ret_succeeded)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582732368,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1358",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:shrink_page_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582732368,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1871
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason, unsigned int * ret_succeeded)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583256832,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1427",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:demote_folio_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583256832,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1906
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
int migrate_pages(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, unsigned int * ret_succeeded)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477888,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1883",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:demote_folio_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477888,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1291
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
int migrate_pages(struct list_head * from, new_folio_t * get_new_folio, free_folio_t * put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, unsigned int * ret_succeeded)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583670368,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1906",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:demote_folio_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:migrate_misplaced_folio",
        "mm/migrate.c:move_pages_and_store_status",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670368,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1227
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493109616,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493109616,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3260
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226806164,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226806164,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2400
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286584288,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286584288,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 4800
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272956034,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272956034,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2070
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581635184,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635184,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2966
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576144,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576144,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2966
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581626496,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581626496,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2966
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
int migrate_pages(struct list_head * from, new_page_t * get_new_page, free_page_t * put_new_page, long unsigned int private, enum migrate_mode mode, int reason)
```

```json
{
  "name": "migrate_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581692816,
      "name": "migrate_pages",
      "external": true,
      "loc": "mm/migrate.c:1399",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:migrate_misplaced_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581692816,
      "name": "migrate_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2957
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int * ret_succeeded</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>new_folio_t * get_new_folio</code>
</li>
<li>
<b>Param added. </b>
<code>free_folio_t * put_new_folio</code>
</li>
<li>
<b>Param removed. </b>
<code>new_page_t * get_new_page</code>
</li>
<li>
<b>Param removed. </b>
<code>free_page_t * put_new_page</code>
</li>
</ul>
</details>
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
