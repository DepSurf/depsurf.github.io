# Function: <code>mem_cgroup_migrate</code>

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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581090080,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:5632",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090080,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581165088,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:5617",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165088,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212880,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:5679",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_copy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212880,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581343424,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:5779",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581343424,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581490896,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:5847",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581490896,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581576752,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6178",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581576752,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581688032,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6470",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581688032,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761488,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761488,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581980800,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6670",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581980800,
      "name": "mem_cgroup_migrate",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582031008,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6930",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582031008,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057696,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6791",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057696,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582365696,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6970",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582365696,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
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
void mem_cgroup_migrate(struct folio * old, struct folio * new)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582863408,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6953",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_replace_page",
        "mm/migrate.c:folio_migrate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582863408,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 400
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
void mem_cgroup_migrate(struct folio * old, struct folio * new)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583410848,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:7142",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/migrate.c:folio_migrate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583410848,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void mem_cgroup_migrate(struct folio * old, struct folio * new)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631104,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:7210",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_folio",
        "mm/shmem.c:shmem_replace_folio",
        "mm/migrate.c:folio_migrate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631104,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void mem_cgroup_migrate(struct folio * old, struct folio * new)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826288,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:7588",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_replace_folio",
        "mm/migrate.c:folio_migrate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826288,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493215496,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493215496,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226846556,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226846556,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286728032,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286728032,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272991830,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272991830,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730224,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730224,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581668992,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581668992,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581721536,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581721536,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 332
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
```

```json
{
  "name": "mem_cgroup_migrate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581789616,
      "name": "mem_cgroup_migrate",
      "external": true,
      "loc": "mm/memcontrol.c:6810",
      "file": "mm/memcontrol.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:replace_page_cache_page",
        "mm/shmem.c:shmem_swapin_page",
        "mm/migrate.c:migrate_page_states"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581789616,
      "name": "mem_cgroup_migrate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 354
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
void mem_cgroup_migrate(struct page * oldpage, struct page * newpage)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * old</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio * new</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * oldpage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * newpage</code>
</li>
</ul>
</details>
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
