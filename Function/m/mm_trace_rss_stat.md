# Function: <code>mm_trace_rss_stat</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mm_trace_rss_stat(struct mm_struct * mm, int member, long int count)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581517958,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:157",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/khugepaged.c:__collapse_huge_page_copy",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/exec.c:acct_arg_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581522320,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
void mm_trace_rss_stat(struct mm_struct * mm, int member, long int count)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581563665,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:159",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/exec.c:acct_arg_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566544,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void mm_trace_rss_stat(struct mm_struct * mm, int member, long int count)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581604036,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:171",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/shmem.c:shmem_mfill_atomic_pte",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/userfaultfd.c:mcopy_atomic_pte",
        "fs/exec.c:acct_arg_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581588848,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void mm_trace_rss_stat(struct mm_struct * mm, int member, long int count)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581870250,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:170",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/exec.c:acct_arg_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581855504,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void mm_trace_rss_stat(struct mm_struct * mm, int member, long int count)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582265486,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:174",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range",
        "mm/memory.c:add_mm_counter_fast",
        "mm/memory.c:sync_mm_rss"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/exec.c:acct_arg_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249936,
      "name": "mm_trace_rss_stat",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mm_trace_rss_stat(struct mm_struct * mm, int member)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582757431,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:165",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/exec.c:free_bprm",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:get_arg_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582741424,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void mm_trace_rss_stat(struct mm_struct * mm, int member)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582973248,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:180",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pte",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/exec.c:free_bprm",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:get_arg_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582957760,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void mm_trace_rss_stat(struct mm_struct * mm, int member)
```

```json
{
  "name": "mm_trace_rss_stat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583150944,
      "name": "mm_trace_rss_stat",
      "external": true,
      "loc": "mm/memory.c:178",
      "file": "mm/memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/memory.c:set_pte_range",
        "mm/memory.c:set_pte_range",
        "mm/memory.c:do_set_pmd",
        "mm/memory.c:do_anonymous_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:do_swap_page",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:wp_page_copy",
        "mm/memory.c:zap_pte_range",
        "mm/memory.c:copy_pte_range"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "kernel/events/uprobes.c:__replace_page",
        "mm/rmap.c:try_to_migrate_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/rmap.c:try_to_unmap_one",
        "mm/madvise.c:madvise_free_pte_range",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/swapfile.c:unuse_pte",
        "mm/ksm.c:replace_page",
        "mm/migrate_device.c:migrate_vma_insert_page",
        "mm/huge_memory.c:__split_huge_pmd_locked",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:zap_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:copy_huge_pmd",
        "mm/huge_memory.c:__do_huge_pmd_anonymous_page",
        "mm/khugepaged.c:collapse_pte_mapped_thp",
        "mm/userfaultfd.c:mfill_atomic_install_pte",
        "fs/exec.c:free_bprm",
        "fs/exec.c:begin_new_exec",
        "fs/exec.c:get_arg_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136048,
      "name": "mm_trace_rss_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mm_trace_rss_stat(struct mm_struct * mm, int member, long int count)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
