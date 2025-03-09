# Function: <code>psi_memstall_leave</code>

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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579826192,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:602",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579826192,
      "name": "psi_memstall_leave",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579856048,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:842",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579856048,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904576,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579904576,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579949664,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:890",
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
      "addr": 18446744071579949664,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579938176,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:906",
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
      "addr": 18446744071579938176,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579945392,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:918",
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
      "addr": 18446744071579945392,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:933",
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
      "addr": 18446744071592121707,
      "name": "psi_memstall_leave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580072432,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:931",
      "file": "kernel/sched/build_utility.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_folio",
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
      "addr": 18446744071593891190,
      "name": "psi_memstall_leave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580205424,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580396011,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:1052",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
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
      "addr": 18446744071595983345,
      "name": "psi_memstall_leave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580395968,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 214
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580464459,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:1075",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
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
      "addr": 18446744071596501737,
      "name": "psi_memstall_leave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580464416,
      "name": "psi_memstall_leave",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580524155,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:1067",
      "file": "kernel/sched/build_utility.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:filemap_read_folio",
        "mm/filemap.c:migration_entry_wait_on_locked",
        "mm/filemap.c:folio_wait_bit_common",
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
      "addr": 18446744071597399423,
      "name": "psi_memstall_leave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071580524112,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491104288,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
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
      "addr": 18446603336491104288,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225110084,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 3225110084,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283996080,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 13835058055283996080,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271687040,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446743936271687040,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876688,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579876688,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811680,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579811680,
      "name": "psi_memstall_leave",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579864848,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579864848,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void psi_memstall_leave(long unsigned int * flags)
```

```json
{
  "name": "psi_memstall_leave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910224,
      "name": "psi_memstall_leave",
      "external": true,
      "loc": "kernel/sched/psi.c:843",
      "file": "kernel/sched/psi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:generic_file_buffered_read",
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
      "addr": 18446744071579910224,
      "name": "psi_memstall_leave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void psi_memstall_leave(long unsigned int * flags)
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
