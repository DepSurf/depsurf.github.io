# Function: <code>__inc_node_page_state</code>

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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708112,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:341",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708112,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580773936,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:341",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/swap_state.c:__add_to_swap_cache",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580773936,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580810384,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:341",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810384,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580900000,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:416",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900000,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581035808,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:416",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581035808,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581113392,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:416",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_replace_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581113392,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581178048,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_shmem",
        "mm/khugepaged.c:collapse_shmem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581178048,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236160,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236160,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581420960,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581420960,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581465680,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:424",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581465680,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486480,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:430",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486480,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581740096,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:462",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/page-writeback.c:account_page_dirtied"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581740096,
      "name": "__inc_node_page_state",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582121552,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:491",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582121552,
      "name": "__inc_node_page_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582595456,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:482",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582595456,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582803584,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:483",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582803584,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980672,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:482",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980672,
      "name": "__inc_node_page_state",
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492630560,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492630560,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226476956,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226476956,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285947968,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285947968,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272650952,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272650952,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581205008,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581205008,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581151760,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151760,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581196208,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196208,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
```

```json
{
  "name": "__inc_node_page_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581259488,
      "name": "__inc_node_page_state",
      "external": true,
      "loc": "mm/vmstat.c:417",
      "file": "mm/vmstat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__add_to_page_cache_locked",
        "mm/filemap.c:replace_page_cache_page",
        "mm/filemap.c:replace_page_cache_page",
        "mm/page-writeback.c:account_page_dirtied",
        "mm/shmem.c:shmem_swapin_page",
        "mm/shmem.c:shmem_add_to_page_cache",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_file_rmap",
        "mm/rmap.c:page_add_new_anon_rmap",
        "mm/rmap.c:do_page_add_anon_rmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581259488,
      "name": "__inc_node_page_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void __inc_node_page_state(struct page * page, enum node_stat_item item)
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
