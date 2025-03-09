# Function: <code>find_get_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580471152,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1030",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:find_lock_entry",
        "mm/filemap.c:pagecache_get_page",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:SyS_madvise",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580471152,
      "name": "find_get_entry",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580552128,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1073",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:SyS_madvise",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580552128,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580616640,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1175",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:SyS_madvise",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580616640,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580646096,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1301",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580646096,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580729536,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1423",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729536,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864912,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1423",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864912,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935664,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1468",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935664,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030656,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1516",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030656,
      "name": "find_get_entry",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581086160,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086160,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581276880,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1500",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:madvise_willneed",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276880,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int index)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581323808,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1691",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/swap_state.c:find_get_incore_page",
        "mm/swap_state.c:get_shadow_from_swap_cache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581323808,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581346598,
      "name": "find_get_entry",
      "external": false,
      "loc": "mm/filemap.c:1916",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581593972,
      "name": "find_get_entry",
      "external": false,
      "loc": "mm/filemap.c:1971",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_get_entry",
      "external": false,
      "loc": "mm/filemap.c:2023",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:find_get_pages_range",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries"
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
  "name": "find_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_get_entry",
      "external": false,
      "loc": "mm/filemap.c:1997",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:find_get_pages_range_tag",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_get_entry",
      "external": false,
      "loc": "mm/filemap.c:1968",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:filemap_get_folios",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "find_get_entry",
      "external": false,
      "loc": "mm/filemap.c:1954",
      "file": "mm/filemap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/filemap.c:mapping_seek_hole_data",
        "mm/filemap.c:filemap_get_folios_tag",
        "mm/filemap.c:find_lock_entries",
        "mm/filemap.c:find_get_entries"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492452456,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492452456,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226326008,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226326008,
      "name": "find_get_entry",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285726800,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285726800,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272524384,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__se_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272524384,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055008,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055008,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581002256,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581002256,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046208,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type",
        "fs/proc/task_mmu.c:smaps_pte_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046208,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct page * find_get_entry(struct address_space * mapping, long unsigned int offset)
```

```json
{
  "name": "find_get_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581107888,
      "name": "find_get_entry",
      "external": true,
      "loc": "mm/filemap.c:1525",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:pagecache_get_page",
        "mm/filemap.c:find_lock_entry",
        "mm/mincore.c:mincore_page",
        "mm/madvise.c:__do_sys_madvise",
        "mm/memcontrol.c:get_mctgt_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581107888,
      "name": "find_get_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct page * find_get_entry(struct address_space * mapping, long unsigned int index)
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
