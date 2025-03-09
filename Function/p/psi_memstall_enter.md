# Function: <code>psi_memstall_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826064,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:572",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826064,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579855904,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:812",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579855904,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904432,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904432,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949520,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:860",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949520,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937984,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:876",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_blkg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937984,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945200,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:888",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:try_charge",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579945200,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:903",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592121687,
      "name": "psi_memstall_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580072224,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:901",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:__folio_lock_or_retry",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593891169,
      "name": "psi_memstall_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580205184,
      "name": "psi_memstall_enter",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:1021",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595983324,
      "name": "psi_memstall_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580395712,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:1044",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_readpage",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596501716,
      "name": "psi_memstall_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580464160,
      "name": "psi_memstall_enter",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:1036",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:readahead_expand",
        "mm/readahead.c:read_pages",
        "mm/vmscan.c:__node_reclaim",
        "mm/vmscan.c:balance_pgdat",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/page_io.c:swap_read_folio",
        "mm/memcontrol.c:try_charge_memcg",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "mm/memcontrol.c:reclaim_high",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597399402,
      "name": "psi_memstall_enter.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580523856,
      "name": "psi_memstall_enter",
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491104072,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:wait_on_page_bit_common",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491104072,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225109892,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225109892,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283995792,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283995792,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271686826,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271686826,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876544,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876544,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811552,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811552,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864704,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579864704,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void psi_memstall_enter(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_enter",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910096,
      "name": "psi_memstall_enter",
      "external": true,
      "loc": "kernel/sched/psi.c:813",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:__lock_page_killable",
        "mm/filemap.c:__lock_page",
        "mm/filemap.c:put_and_wait_on_page_locked",
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_mem_cgroup_pages",
        "mm/compaction.c:kcompactd",
        "mm/page_alloc.c:__alloc_pages_slowpath",
        "mm/page_alloc.c:__alloc_pages_direct_compact",
        "mm/memcontrol.c:mem_cgroup_handle_over_high",
        "block/blk-core.c:submit_bio",
        "block/blk-cgroup.c:blkcg_maybe_throttle_current"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910096,
      "name": "psi_memstall_enter",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void psi_memstall_enter(long unsigned int * flags)
```
</details>
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
