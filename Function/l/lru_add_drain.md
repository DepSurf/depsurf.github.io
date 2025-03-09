# Function: <code>lru_add_drain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541225,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:857",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/swap.c:__pagevec_release"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_inactive_list",
        "mm/vmscan.c:shrink_active_list",
        "mm/shmem.c:shmem_add_seals",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:unmap_region",
        "mm/mmap.c:exit_mmap",
        "mm/madvise.c:force_swapin_readahead",
        "mm/madvise.c:SyS_madvise",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/swap_state.c:swapin_readahead",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580541440,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580629517,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:658",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_seals",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:force_swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580629936,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580696733,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:659",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_seals",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/madvise.c:SyS_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:force_swapin_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580697152,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580730509,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:678",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_seals",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:madvise_willneed",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580730928,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580816515,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:678",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/shmem.c:shmem_add_seals",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/fadvise.c:SyS_fadvise64",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:madvise_willneed",
        "mm/swap_state.c:do_swap_page_readahead",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580816992,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580953589,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:651",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/fadvise.c:ksys_fadvise64_64",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:madvise_willneed",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/memfd.c:memfd_fcntl",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954000,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581029749,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:645",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:madvise_willneed",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/memfd.c:memfd_fcntl",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030192,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581093781,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:646",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:vfs_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:madvise_willneed",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581094192,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581150565,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581151152,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581336217,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:731",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:madvise_willneed",
        "mm/madvise.c:madvise_willneed",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_prep_local",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581336928,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581379801,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:717",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/migrate.c:migrate_prep_local",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379552,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581400761,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:721",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581400512,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581651624,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:698",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_prepare",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651360,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582020416,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:703",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate_device.c:migrate_vma_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020096,
      "name": "lru_add_drain",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582453088,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:783",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:lru_gen_shrink_lruvec",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/madvise.c:force_shm_swapin_readahead",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582453936,
      "name": "lru_add_drain",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582658368,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:749",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__folio_batch_release"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_node",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_page_range_single",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582659136,
      "name": "lru_add_drain",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582829504,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:749",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__folio_batch_release"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_lruvec",
        "mm/vmscan.c:lru_gen_shrink_node",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/compaction.c:compact_zone",
        "mm/gup.c:faultin_vma_page_range",
        "mm/gup.c:populate_vma_page_range",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_wp_page",
        "mm/memory.c:zap_page_range_single",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mlock.c:mlock_fixup",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_vma_behavior",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swap_vma_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_pages_batch",
        "mm/migrate_device.c:migrate_device_unmap",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:collapse_file",
        "mm/khugepaged.c:__collapse_huge_page_swapin",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582830256,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492527720,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:__arm64_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492527720,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226394240,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:setup_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226395044,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285821344,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285822400,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272580718,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:__se_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_prep_local",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272581432,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581119413,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581120000,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581066405,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066992,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581110613,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu"
      ],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581111200,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
void lru_add_drain()
```

```json
{
  "name": "lru_add_drain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581173600,
      "name": "lru_add_drain",
      "external": true,
      "loc": "mm/swap.c:687",
      "file": "mm/swap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/fadvise.c:generic_fadvise",
        "mm/swap.c:__pagevec_release",
        "mm/swap.c:lru_add_drain_per_cpu",
        "mm/vmscan.c:shrink_active_list",
        "mm/vmscan.c:shrink_inactive_list",
        "mm/gup.c:follow_page_pte",
        "mm/memory.c:zap_page_range_single",
        "mm/memory.c:zap_page_range",
        "mm/mmap.c:exit_mmap",
        "mm/mmap.c:unmap_region",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:__do_sys_madvise",
        "mm/madvise.c:madvise_free_single_vma",
        "mm/madvise.c:madvise_pageout",
        "mm/madvise.c:madvise_cold",
        "mm/swap_state.c:swapin_readahead",
        "mm/swap_state.c:swap_cluster_readahead",
        "mm/swap_state.c:free_pages_and_swap_cache",
        "mm/migrate.c:migrate_vma_setup",
        "mm/migrate.c:migrate_prep_local",
        "mm/huge_memory.c:split_huge_page_to_list",
        "mm/huge_memory.c:follow_trans_huge_pmd",
        "mm/khugepaged.c:collapse_file",
        "mm/memfd.c:memfd_wait_for_pins",
        "fs/exec.c:shift_arg_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173600,
      "name": "lru_add_drain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
