# Function: <code>putback_movable_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580881680,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:83",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:isolate_migratepages_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/migrate.c:SyS_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580881680,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012864,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:160",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_migrate_pages",
        "mm/migrate.c:SyS_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012864,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087040,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:160",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:SYSC_move_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087040,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 338
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134608,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:162",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134608,
      "name": "putback_movable_pages",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252592,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:166",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252592,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398720,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:167",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398720,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581482320,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:167",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482320,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 418
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593360,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:167",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593360,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661440,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661440,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882768,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:169",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882768,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928784,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:165",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928784,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954128,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:138",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954128,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258864,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:139",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258864,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724464,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:138",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724464,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 694
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250064,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:147",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250064,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 683
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583470112,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:147",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/gup.c:migrate_longterm_unpinnable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470112,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 371
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583662400,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:147",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/page_alloc.c:__alloc_contig_migrate_range",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/migrate.c:move_pages_and_store_status",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662400,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493107128,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493107128,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226803916,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226803916,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286576608,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286576608,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 740
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272954090,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272954090,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630176,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630176,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571232,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571232,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621488,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621488,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
void putback_movable_pages(struct list_head * l)
```

```json
{
  "name": "putback_movable_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687872,
      "name": "putback_movable_pages",
      "external": true,
      "loc": "mm/migrate.c:168",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:compact_zone",
        "mm/compaction.c:isolate_migratepages_block",
        "mm/gup.c:__gup_longterm_locked",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/page_alloc.c:alloc_contig_range",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:migrate_to_node",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687872,
      "name": "putback_movable_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 426
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
