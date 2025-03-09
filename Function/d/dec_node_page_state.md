# Function: <code>dec_node_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580706688,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:517",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/khugepaged.c:collapse_huge_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580706688,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767232,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:517",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:test_clear_page_writeback",
        "mm/page-writeback.c:clear_page_dirty_for_io",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:khugepaged",
        "mm/khugepaged.c:khugepaged",
        "mm/memory-failure.c:soft_offline_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767232,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580803712,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:517",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:putback_movable_pages",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580803712,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580892432,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:592",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580892432,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028608,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:592",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028608,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581106144,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:592",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581106144,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581170768,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581170768,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581228800,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581228800,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581421344,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "fs/fuse/file.c:fuse_writepage_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581421344,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581466672,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:607",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "fs/fuse/file.c:fuse_writepage_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581466672,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485744,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:619",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "fs/fuse/file.c:fuse_writepage_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485744,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581742576,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:665",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581742576,
      "name": "dec_node_page_state",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582124432,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:694",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582124432,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582597104,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:681",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582597104,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806640,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:682",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806640,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 242
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582979328,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:683",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582979328,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492626824,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492626824,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226477568,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:668",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226477568,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285948784,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:668",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285948784,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272651714,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:668",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272651714,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581197648,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581197648,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581144400,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581144400,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581188848,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581188848,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void dec_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "dec_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252176,
      "name": "dec_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:593",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_redirty",
        "mm/page-writeback.c:account_page_redirty",
        "mm/migrate.c:migrate_misplaced_page",
        "mm/khugepaged.c:release_pte_page",
        "fs/fuse/file.c:fuse_writepages_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252176,
      "name": "dec_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dec_node_page_state(struct page * page, enum node_stat_item item)
```
</details>
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
