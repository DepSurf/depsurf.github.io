# Function: <code>mlock_vma_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692720,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:80",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692720,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806688,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:80",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_with_ksm_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806688,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871744,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:80",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871744,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916736,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:81",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916736,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016144,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:82",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016144,
      "name": "mlock_vma_page",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581150608,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581150608,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230432,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230432,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581304752,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581304752,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581363328,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363328,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581560528,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581560528,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581605648,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:90",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581605648,
      "name": "mlock_vma_page",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628320,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:90",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628320,
      "name": "mlock_vma_page",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581896000,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:91",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:restore_exclusive_pte",
        "mm/rmap.c:page_mlock_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896000,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582372239,
      "name": "mlock_vma_page",
      "external": false,
      "loc": "mm/internal.h:527",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap"
      ],
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582874902,
      "name": "mlock_vma_page",
      "external": false,
      "loc": "mm/internal.h:525",
      "file": "mm/rmap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_anon_rmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492768752,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492768752,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226587288,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226587288,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286133808,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286133808,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272745746,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272745746,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581332176,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332176,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275888,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275888,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323376,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323376,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
```

```json
{
  "name": "mlock_vma_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581387376,
      "name": "mlock_vma_page",
      "external": true,
      "loc": "mm/mlock.c:88",
      "file": "mm/mlock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/gup.c:follow_page_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/ksm.c:try_to_merge_one_page",
        "mm/migrate.c:remove_migration_pte",
        "mm/huge_memory.c:remove_migration_pmd",
        "mm/huge_memory.c:follow_trans_huge_pmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387376,
      "name": "mlock_vma_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void mlock_vma_page(struct page * page)
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
