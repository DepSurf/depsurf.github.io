# Function: <code>wait_on_page_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580469520,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:746",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/filemap.c:wait_on_page_read",
        "mm/filemap.c:filemap_fault",
        "mm/page-writeback.c:write_cache_pages",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:__migration_entry_wait",
        "mm/migrate.c:migrate_pages",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/memory-failure.c:memory_failure",
        "mm/memory-failure.c:soft_offline_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580469520,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
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
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580547328,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:786",
      "file": "mm/filemap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_fdatawait_range",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580547328,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580618640,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:883",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": [
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580615072,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580648418,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1009",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": [
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580644992,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580732288,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1130",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/memory-failure.c:soft_offline_page",
        "mm/memory-failure.c:memory_failure",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580726976,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580867843,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1130",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:migrate_pages",
        "mm/migrate.c:pmd_migration_entry_wait",
        "mm/migrate.c:__migration_entry_wait",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/huge_memory.c:do_huge_pmd_numa_page",
        "mm/memory-failure.c:soft_offline_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863680,
      "name": "wait_on_page_bit",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580938940,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1164",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__filemap_fdatawait_range"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_for_stable_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_one_page",
        "mm/page-writeback.c:write_cache_pages",
        "mm/truncate.c:invalidate_inode_pages2_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/truncate.c:truncate_inode_pages_range",
        "mm/vmscan.c:shrink_page_list",
        "mm/shmem.c:shmem_getpage_gfp",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/swapfile.c:try_to_unuse",
        "mm/hugetlb.c:hugetlb_fault",
        "mm/migrate.c:migrate_pages",
        "mm/memory-failure.c:soft_offline_page",
        "fs/splice.c:page_cache_pipe_buf_steal",
        "fs/ext4/inode.c:mpage_prepare_extent_to_map",
        "fs/ext4/move_extent.c:move_extent_per_page",
        "fs/ext4/move_extent.c:move_extent_per_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580933120,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 522
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581033246,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1212",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581027440,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581088814,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082784,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581281269,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1196",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268640,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581325253,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1335",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313616,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336974,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1359",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:wait_on_page_private_2"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581332176,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581585279,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1414",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:__lock_page_or_retry",
        "mm/filemap.c:wait_on_page_private_2"
      ],
      "caller_func": [
        "mm/page-writeback.c:wait_on_page_writeback",
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581579856,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492455480,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492447880,
      "name": "wait_on_page_bit",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226329048,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226320908,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285730944,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285719392,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 800
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272526556,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272522780,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581057662,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051632,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581004910,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580998896,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581048862,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581042832,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void wait_on_page_bit(struct page * page, int bit_nr)
```

```json
{
  "name": "wait_on_page_bit",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581110542,
      "name": "wait_on_page_bit",
      "external": true,
      "loc": "mm/filemap.c:1221",
      "file": "mm/filemap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:do_read_cache_page",
        "mm/filemap.c:filemap_fault",
        "mm/filemap.c:__lock_page_or_retry"
      ],
      "caller_func": [
        "mm/hugetlb.c:hugetlb_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581104480,
      "name": "wait_on_page_bit",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 534
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
void wait_on_page_bit(struct page * page, int bit_nr)
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
