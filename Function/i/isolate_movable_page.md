# Function: <code>isolate_movable_page</code>

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
bool isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012496,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:77",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012496,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
bool isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086672,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:77",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086672,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 315
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134304,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:79",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134304,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581252240,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:83",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581252240,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581398320,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:84",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581398320,
      "name": "isolate_movable_page",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581481920,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:84",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581481920,
      "name": "isolate_movable_page",
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581593024,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:84",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581593024,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581661104,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581661104,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581882432,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:86",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581882432,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581928448,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:82",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:isolate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581928448,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581953840,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:60",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953840,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582258576,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:61",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258576,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582724080,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:60",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582724080,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 381
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583249456,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:61",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249456,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
bool isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469856,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:60",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469856,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
bool isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583662144,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:60",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/memory-failure.c:soft_offline_in_use_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583662144,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493106600,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493106600,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 448
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226803376,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226803376,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 476
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286575856,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286575856,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272953772,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272953772,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581629840,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629840,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581570896,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570896,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621152,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621152,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
int isolate_movable_page(struct page * page, isolate_mode_t mode)
```

```json
{
  "name": "isolate_movable_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581687536,
      "name": "isolate_movable_page",
      "external": true,
      "loc": "mm/migrate.c:85",
      "file": "mm/migrate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/memory_hotplug.c:do_migrate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581687536,
      "name": "isolate_movable_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
bool isolate_movable_page(struct page * page, isolate_mode_t mode)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
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
