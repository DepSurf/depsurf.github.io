# Function: <code>isolate_huge_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580809856,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4416",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:SyS_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580809856,
      "name": "isolate_huge_page",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934432,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4437",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:SyS_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934432,
      "name": "isolate_huge_page",
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002736,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4550",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002736,
      "name": "isolate_huge_page",
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050016,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4703",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050016,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160976,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4783",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:SYSC_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160976,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304144,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4812",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304144,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387808,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:4901",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:__offline_pages",
        "mm/migrate.c:kernel_move_pages",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387808,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581499472,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5006",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581499472,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581563984,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581563984,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581774608,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5622",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:add_page_for_migration"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581774608,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581822752,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5634",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:add_page_for_migration",
        "mm/memory-failure.c:isolate_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581822752,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581851952,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5914",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:add_page_for_migration",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581851952,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582143328,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:6251",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:check_and_migrate_movable_pages",
        "mm/hugetlb.c:isolate_or_dissolve_huge_page",
        "mm/hugetlb.c:alloc_and_dissolve_huge_page",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:add_page_for_migration",
        "mm/memory-failure.c:__soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582143328,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492998512,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/migrate.c:do_pages_move",
        "mm/memory-failure.c:soft_offline_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492998512,
      "name": "isolate_huge_page",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "isolate_huge_page",
      "external": false,
      "loc": "include/linux/hugetlb.h:190",
      "file": "mm/gup.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286425392,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286425392,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 376
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272900256,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272900256,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581532720,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532720,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581474496,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581474496,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581524032,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581524032,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```

```json
{
  "name": "isolate_huge_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581588960,
      "name": "isolate_huge_page",
      "external": true,
      "loc": "mm/hugetlb.c:5123",
      "file": "mm/hugetlb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:__gup_longterm_locked",
        "mm/mempolicy.c:queue_pages_hugetlb",
        "mm/memory_hotplug.c:do_migrate_range",
        "mm/migrate.c:do_pages_move"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588960,
      "name": "isolate_huge_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
bool isolate_huge_page(struct page * page, struct list_head * list)
```
</details>
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
bool isolate_huge_page(struct page * page, struct list_head * list)
```
</details>
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
